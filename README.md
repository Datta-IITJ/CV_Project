# CV_Project 
# TITLE: WATERMARKING IN IMAGES<br>

## Overview

This is a Computer Vision project focused on exploring different ways of protecting image copyright through image watermarking and identifying potential flaws in the process. The project aims to implement watermarking techniques, such as visible and invisible watermarking through logos and text, and evaluate their effectiveness in protecting copyright. It also explores potential flaws or weaknesses in the watermarking process and develops strategies to strengthen image protection. Additionally, the project uses evaluation measures to check watermarking techniques used and provides results accordingly for comparison purposes.<br>

Name of Students:<br>
1. Vandita Agarwal<br>
2. Shilajit Banerjee<br>
3. Dattatreyo Roy<br>

This is the Computer Vision project 1.

The main objective of the project is to explore different ways of protecting image copyright through image watermarking and identifying potential flaws in the process.
The project will implement watermarking techniques such as visible and invisible watermarking through logos and text and evaluate their effectiveness in protecting copyright.
After then it will implement techniques to remove that watermark from the watermarked images, so as to receive almost original images again. The project will also explore potential flaws or weaknesses in the watermarking process and develop strategies to strengthen image protection. Ultimately, it will also use evaluation measures to check watermarking techniques used and give results accordingly, so that we could compare these techniques.<br>

## Normal Watermark

Here is the logo we have used for watermarking purpose.<br>
<p align="center">
  <img src="Images/3.jpeg" alt="image_description" width="200"/><br>
 </p>
After adding this and removing we got the following images: <br>
<p align="center">
  <img src="Images/77.png" alt="image_description" width="750"/><br>
</p><br>
We have also used text at random positions for watermarking as well. As you can see - 
<p align="center">
  <img src="Images/WhatsApp Image 2023-03-18 at 7.08.12 PM.jpeg" alt="image_description" width="300"/>
</p>

### Techniques

For removal of the watermark we have used different techniques. Like for image watermark removal we have used the following methods -
For the detection of the watermark the methods used are-
1. Template Matching<br>
2. Sift<br>
3. ORB<br>
After detecting these we have used inpainting method to remove the image watermark. We have tried to do by replacing the mean value of the pixels but that didnot gave good results. <br>
For text detection and removal we have used sate of the art OCR methods. Like you can see below-><br><br>
<p align="center">
  <img src="Images/t1.jpg" alt="image_description" width="300"/><br>
</p>
After removing this got the following result - <br>
<p align="center">
  <img src="Images/t2.png" alt="image_description" width="300"/><br>
</p>
We have also used text at random positions for watermarking as well.<br>

### Evaluation Metrics

For evaluating the watermarking techniques, we have used different loss functions to calculate the loss between the (original image, watermarked image) and (original image, watermark-removed image). The loss functions we have used are:
The used evaluation metrices are-
1. MSE Loss <br>
2. Log Loss <br>
3. Pairwise Loss <br>
We have calculated the loss for each pairs. I am giving an example of loss plot - <br><br>
<p align="center">
  <img src="Images/33.png" alt="image_description" width="300"/><br>
</p><br>
As we can see the loss after adding the watermark and It's in the range of 1 which is good. That means we are chaning very few pixels in the image.<br>
After removing these watermark here is the loss - <br><br>
<p align="center">
  <img src="Images/1.png" alt="image_description" width="300"/><br>
</p>

## Rotated Watermark

Another aspect of our project is the rotated watermark. We will be adding the same image watermark but that will be rotated so, that finding the watermark in the image becomed difficult. In such cases ORB, SIFT methods have worked well. Here is an example of rotated watermark- <br><br>
<p align="center">
  <img src="Images/22.1.png" alt="image_description" width="300"/><br>
</p><br>
Here in the example you can see we have added the rotated watermark - <br><br>
<p align="center">
  <img src="Images/2.png" alt="image_description" width="300"/><br>
</p><br>
After removing this we got - <br><br>
<p align="center">
  <img src="Images/3.png" alt="image_description" width="400"/><br>
</p><br>

## Conclusion
In conclusion, this project has explored various watermarking techniques and evaluated their effectiveness in protecting image copyright. We have also identified potential flaws in the watermarking process and developed strategies to strengthen image protection. By using evaluation metrics, we have compared different watermarking techniques and provided results accordingly.<br>
