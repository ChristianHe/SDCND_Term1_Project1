# **Finding Lane Lines on the Road**

## 1. Pipeline Description
My pipeline consisted of 5 steps. 

** Convert the images into grayscale

** Use the Canny edge detection to detect the edges of the image, 

** ROI is then used to select the area of interest edges.

** Use Hough Transform to get the Lane line segments.

** In order to draw a single line on the left and right lanes, draw_lines() function 
is modified. Polyfit is used to get the 




In order to draw a single line on the left and right lanes, I modified the draw_lines() function by ...

If you'd like to include images to show how the pipeline works, here is how to include an image: 


Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

My pipeline consisted of 5 steps. First, I converted the images to grayscale, then I .... 

In order to draw a single line on the left and right lanes, I modified the draw_lines() function by ...

If you'd like to include images to show how the pipeline works, here is how to include an image: 

![alt text][image1]


## 2. Shortcomes
Identify potential shortcomings with your current pipeline


One potential shortcoming would be what would happen when ... 

Another shortcoming could be ...


## 3. Suggestions

A possible improvement would be to ...

Another potential improvement could be to ...
