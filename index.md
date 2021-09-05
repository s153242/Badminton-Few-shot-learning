## Welcome to my website
This website seeks to stand as support to my thesis Few-Shot Action Recognition for BadmintonStroke Classification. On the website I will show different data examples and model results. It should be seen as a tool for better visualizing the findigs as presenting video data in a paper information can quickly be lost.

## Data Presentation

I will give a quick overview of the data content used in this work. I annotated three different matches. A short clip from each match is presented below in the order: match 1 (Axelsen vs Chen), match 2 (Chen vs Axelsen), match 3 (Nishimito vs Vincent)

<p float="left">
  
  <video src="Axel_Chen_clip_14_7.mp4" width="250" height="250" controls preload></video>
  <video src="Chen_video_1_clip.mp4" width="250" height="250" controls preload></video>
  <video src="nish_vinc_point_1.mp4" width="250" height="250" controls preload></video>
  
</p>
In this work I distinguish between five stroke types: Smash, Net, Lop, Backhand and serve divided into eight categories due to differentiating left and right movement of Lop, Net and smash.  In addition, this work test two different video crop types: Half-field crop and Player-crop. Down below is shown two data samples for each shot type for both video crop types.

## Half-court Crop
Half-court crop extracts the side of the court the player modeled is on. In my case it is always the player closest to the camera to simplify the problem. 
**Smash**
<p>
  <video src="smash_left1.mp4" width="250" height="200" controls preload></video>
  <video src="smash_right1.mp4" width="250" height="200" controls preload></video>
</p>
<p float="left">
  **NET: **
  <video src="net_left1.mp4" width="250" height="250" controls preload></video>
  <video src="net_right1.mp4" width="250" height="250" controls preload></video>
</p>
<p float="left">
  **Lop: **
  <video src="lop_left1.mp4" width="250" height="250" controls preload></video>
  <video src="lop_right1.mp4" width="250" height="250" controls preload></video>
</p>
<p float="left">
  **Backhand: **
  <video src="backhand1.mp4" width="250" height="250" controls preload></video>
  <video src="backhand3.mp4" width="250" height="250" controls preload></video>
</p>
<p float="left">
  **Serve: **
  <video src="serve1.mp4" width="250" height="250" controls preload></video>
  <video src="serve3.mp4" width="250" height="250" controls preload></video>
</p>

## Player-Crop
The player-crop type centers the frame on the player in the beginning of the clip and stays in that space throughout the video. This way you will get the motion of the player out from the center of the frame. It is a closer zoom compared to half-video crop.
<p float="left">
  **SMASH: **
  <video src="ss1.mp4" width="250" height="200" controls preload></video>
  <video src="ss2.mp4" width="250" height="200" controls preload></video>
</p>
<p float="left">
  **NET: **
  <video src="nn1.mp4" width="250" height="250" controls preload></video>
  <video src="nn2.mp4" width="250" height="250" controls preload></video>
</p>
<p float="left">
  **Lop: **
  <video src="ll1.mp4" width="250" height="250" controls preload></video>
  <video src="ll2.mp4" width="250" height="250" controls preload></video>
</p>
<p float="left">
  **Backhand: **
  <video src="bb1.mp4" width="250" height="250" controls preload></video>
  <video src="bb2.mp4" width="250" height="250" controls preload></video>
</p>
<p float="left">
  **Serve: **
  <video src="se1.mp4" width="250" height="250" controls preload></video>
  <video src="se2.mp4" width="250" height="250" controls preload></video>
</p>

# Results
As mentioned in the report, my approach randomly samples a new test set for each run the model perform. For validating the model on a game setup the results thus changes. Some show really good results and other runs do not. Down below I have shown different model results for the validation on the game setup. 

### Chen Axel 9_7 

### without
<p float="left">
  <video src="Chen_Axel_9_7_1_without.mp4" width="320" height="200" controls preload></video>
  <video src="Chen_Axel_9_7_2_without.mp4" width="320" height="200" controls preload></video>
</p>

### With

<p float="left">
  <video src="Chen_Axel_9_7_1_with.mp4" width="320" height="200" controls preload></video>
  <video src="Chen_Axel_9_7_2_with.mp4" width="320" height="200" controls preload></video>
</p>

### Nish Vinc 3_2

### Without

<p float="left">
  <video src="Nish_Vinc_3_2_1_without.mp4" width="320" height="200" controls preload></video>
  <video src="Nish_Vinc_3_2_2_without.mp4" width="320" height="200" controls preload></video>
</p>

### With


<p float="left">
  <video src="Nish_Vinc_3_2_with.mp4" width="320" height="200" controls preload></video>
  <video src="Nish_Vinc_3_2_2_with.mp4" width="320" height="200" controls preload></video>
</p>



**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```
![snip_net.PNG](snip_net.PNG) and ![snip_net.PNG](snip_net.PNG)
For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

<video src="video_test.mp4" width="320" height="200" controls preload></video> and 

<video src="video_test.mp4" width="320" height="200" controls preload></video>

<details>
    <summary>Minhas Estátisticas no Github</summary>
    <p>
        <video align="left" src="video_test.mp4" width="320" height="200" controls preload></video>
                      
        <video align="right" src="video_test.mp4" width="320" height="200" controls preload></video>
    </p>
</details>

<img src="video_test.gif" width="100" height="100">

<p float="left">
  <img src="video_test.gif" width="100" height="100"/>
  <img src="video_test.gif" width="100" height="100"/>
  <img src="video_test.gif" width="100" height="100"/>
</p>

<p float="left">
  <video src="video_test.mp4" width="250" height="250" controls preload></video>
  <video src="video_test.mp4" width="250" height="250" controls preload></video>
  <video src="video_test.mp4" width="250" height="250" controls preload></video>
</p>


![video_gif](video_test.gif)
### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/s153242/Badminton_Few_shot_learning.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
