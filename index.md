# Few-Shot Action Recognition for Badminton Stroke Classification
This website seeks to stand as support to my thesis "Few-Shot Action Recognition for Badminton Stroke Classification". On the website I will show different data examples and results from model-validation on the game setup. It should be seen as a tool for better visualizing the findigs as presenting video data in a paper information quickly can be lost.

## Data Presentation

I will give a quick overview of the data content used in this work. I annotated three different matches. A short clip from each match is presented below in the order: match 1 (Axelsen vs Chen), match 2 (Chen vs Axelsen), match 3 (Nishimito vs Vincent)

<p float="left">
  <video src="Axel_Chen_clip_14_7.mp4" width="250" height="250" controls preload></video>
  <video src="Chen_video_1_clip.mp4" width="250" height="250" controls preload></video>
  <video src="nish_vinc_point_1.mp4" width="250" height="250" controls preload></video>
  
</p>
In this work I distinguish between five stroke types: Smash, Net, Lop, Backhand and Serve divided into eight categories due to differentiating left and right movement of Lop, Net and Smash.  In addition, this work test two different video crop types: Half-field crop and Player-crop. Down below is shown two data samples for each shot type for both video crop types.

## Half-court Crop
Half-court crop extracts the side of the court the player modeled is on. In my case it is always the player closest to the camera to simplify the problem. 
<p>
  <summary>Smash</summary>
  <video src="smash_left1.mp4" width="300" height="200" controls preload></video>
  <video src="smash_right1.mp4" width="300" height="200" controls preload></video>
</p>
<p float="left">
  <summary>Net</summary>
  <video src="net_left1.mp4" width="300" height="200" controls preload></video>
  <video src="net_right1.mp4" width="300" height="200" controls preload></video>
</p>
<p float="left">
  <summary>Lop</summary>
  <video src="lop_left1.mp4" width="300" height="200" controls preload></video>
  <video src="lop_right1.mp4" width="300" height="200" controls preload></video>
</p>
<p float="left">
  <summary>Backhand</summary>
  <video src="backhand1.mp4" width="300" height="200" controls preload></video>
  <video src="backhand3.mp4" width="300" height="200" controls preload></video>
</p>
<p float="left">
  <summary>Serve</summary>
  <video src="serve1.mp4" width="300" height="200" controls preload></video>
  <video src="serve3.mp4" width="300" height="200" controls preload></video>
</p>

## Player-Crop
The player-crop type centers the frame on the player in the beginning of the clip and stays in that space throughout the video. This way you will get the motion of the player out from the center of the frame. It is a closer zoom compared to half-video crop.
<p float="left">
  <summary>Smash</summary>
  <video src="ss1.mp4" width="300" height="200" controls preload></video>
  <video src="ss2.mp4" width="300" height="200" controls preload></video>
</p>
<p float="left">
  <summary>Net</summary>
  <video src="nn1.mp4" width="300" height="200" controls preload></video>
  <video src="nn2.mp4" width="300" height="200" controls preload></video>
</p>
<p float="left">
  <summary>Lop</summary>
  <video src="ll1.mp4" width="300" height="200" controls preload></video>
  <video src="ll2.mp4" width="300" height="200" controls preload></video>
</p>
<p float="left">
  <summary>Backhand</summary>
  <video src="bb1.mp4" width="300" height="200" controls preload></video>
  <video src="bb2.mp4" width="300" height="200" controls preload></video>
</p>
<p float="left">
  <summary>Serve</summary>
  <video src="se1.mp4" width="300" height="200" controls preload></video>
  <video src="se2.mp4" width="300" height="200" controls preload></video>
</p>

# Results - Model-validation Game Setup
Down below I show the videos of the game-validation examples shown in the report. All results are extracted using the two-stream++ approach either with or without fine-tuned features.  

## Match 2 Chen Long vs. Viktor Axelsen, point: 9-7 

#### without Finetuning
<p float="left">
  <video src="Chen_Axel_9_7_1_without.mp4" width="400" height="300" controls preload></video>
  <video src="Chen_Axel_9_7_2_without.mp4" width="400" height="300" controls preload></video>
</p>
#### With Finetuning
<p float="left">
  <video src="Chen_Axel_9_7_1_with.mp4" width="400" height="300" controls preload></video>
  <video src="Chen_Axel_9_7_2_with.mp4" width="400" height="300" controls preload></video>
</p>

## Match 3 Nishimoto vs. Vincent, point: 3-2

#### Without

<p float="left">
  <video src="Nish_Vinc_3_2_1_without.mp4" width="400" height="300" controls preload></video>
  <video src="Nish_Vinc_3_2_2_without.mp4" width="400" height="300" controls preload></video>
</p>

#### With
<p float="left">
  <video src="Nish_Vinc_3_2_with.mp4" width="400" height="300" controls preload></video>
  <video src="Nish_Vinc_3_2_2_with.mp4" width="400" height="300" controls preload></video>
</p>
