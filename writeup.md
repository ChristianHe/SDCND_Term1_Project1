# Finding Lane Lines on the Road

## 1. Pipeline Description
My pipeline consisted of 6 steps. 

** Convert the images into grayscale first.

** Use the Canny edge detection to detect the edges of the gray image, 

** ROI is then used to select the area of interest edges. The region here is quadrangle.

** Use Hough Transform to get the Lane line segments.

** As with the guideline provided, the line segments detected by Hough Transform are 
separated into left and right line according the slope value and the value of x1 and x2. 
The left and right line are then extrapolated separately to the border of the ROI with 
the polyfit api of numpy.

** Finally, Lane lines are  addweighted to the original image.

You can refer to the "P1.ipynb" or "P1.html" for the pipeline, and test images in the folder "test images output".

## 2. Shortcomes
One potential shortcoming would be what would happen when with the challenge video. 

The current pipeline can not tackle with the challenge video.

## 3. Suggestions of improvement
A possible improvement would be not to change the RGB color space to Gray but to 
the HSV space. Under the HSV space, it may pick up the yellow and white lines more
precisely.

I have given it a try, but for some reasons, I failed.

Since the due time is comming, I have to submit the pipeline firstly.

P.S. The reason why I submitted my homework in Zip file was that I failed to upload the files into the GitHub.
Maybe it's a network problem, since we have a GreatWall of network in R.P.China.
Anyway, I will try later to figure this out.
And also any suggestion is appreciated.
