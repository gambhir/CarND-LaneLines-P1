# **Finding Lane Lines on the Road** 

The goals / steps of this project are the following:


In this project, I used Python and OpenCV to find lane lines in the road images.

The following techniques are used:
Grayscale: Convert regular color image to single channel image.
Gaussian Blur:  Applied to smooth out the noise,
Canny Edge Detection: Transform and detect the edges
[image1]: ./edge.png


Region masking: Selecting only portion of image defined by polygon vertices rest is blacked out. 
Hough Transform Line Detection: Detects the linear lines in the image

Since some lanes lines are partically recongnized by using extrapolating technique the lines were extended for continuity. 

Identified the left and right lanes with negative and positive slope. And aftering identifiying left and right took the average. 




