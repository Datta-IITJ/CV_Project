# CV_Project
This is the Computer Vision project 1.

The main objective of the project is to explore different ways of protecting image copyright through image watermarking and identifying potential flaws in the process.
The project will implement watermarking techniques such as visible and invisible watermarking through logos and text and evaluate their effectiveness in protecting copyright.
After then it will implement techniques to remove that watermark from the watermarked images, so as to receive almost original images again. The project will also explore potential flaws or weaknesses in the watermarking process and develop strategies to strengthen image protection. Ultimately, it will also use evaluation measures to check watermarking techniques used and give results accordingly, so that we could compare these techniques.<br>
Here is the logo we have used for watermarking purpose.<br><br>
<p align="center">
  <img src="Images/3.jpeg" alt="image_description" width="300"/><br>
 </p>
After adding this and removing we got the following images: <br><br>
<p align="center">
  <img src="Images/77.png" alt="image_description" width="750"/><br>
</p><br><br>
We have also used text at random positions for watermarking as well. As you can see - 
<p align="center">
  <img src="Images/WhatsApp Image 2023-03-18 at 7.08.12 PM.jpeg" alt="image_description" width="300"/>
</p>
For removal of the watermark we have used different techniques. Like for image watermark removal we have used the following methods - <br>
For the detection of the watermark the methods used are- <br>
1. Template Matching<br>
2. Sift<br>
3. ORB<br>
After detecting these we have used inpainting method to remove the image watermark. We have tried to do by replacing the mean value of the pixels but that didnot gave good results. <br>
For text detection and removal we have used sate of the art OCR methods. Like you can see below-><br><br>
<p align="center">
  <img src="Images/t1.jpg" alt="image_description" width="300"/><br>
</p><br><br>
After removing this got the following result - <br>
<p align="center">
  <img src="Images/t2.png" alt="image_description" width="300"/><br>
</p><br><br>
We have also used text at random positions for watermarking as well.<br>
For the evaluation metrics we have used differnt loss functions for calculation of the loss between the (original image, watermarked image) and (original image, Watermark removed image)<br>
The used evaluation metrices are- <br>
1. MSE Loss <br>
2. Log Loss <br>
3. Pairwise Loss <br>
We have calculated the loss for each pairs. I am giving an example of loss plot - <br><br>
<p align="center">
  <img src="Images/33.png" alt="image_description" width="300"/><br>
</p><br><br>

\newline
