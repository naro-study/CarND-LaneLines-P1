# **Finding Lane Lines on the Road** 

## Writeup Template

### You can use this file as a template for your writeup if you want to submit it as a markdown file. But feel free to use some other method and submit a pdf if you prefer.

---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report


[//]: # (Image References)

[image1]: ./figure/grayscale.jpg "grayscale"

[image2]: ./figure/gaussian_blur.jpg "gaussian blur"

[image3]: ./figure/canny.jpg "canny edge detection"

[image4]: ./figure/roi.jpg "region of interest"

[image5]: ./figure/hough.jpg "hough transform"

[image6]: ./figure/weighted.jpg "result"

---

### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

My pipeline consisted of 6 steps. 
1) I converted the images to grayscale
2) Apply Gaussian blur
3) Apply Canny edge detection
4) Apply region of interest for eliminate non relevant noise
5) Apply Hough transform to detect line segments
6) Separate left and right lanes, and draw the lanes

In order to draw a single line on the left and right lanes, I modified the draw_lines() function by ...

If you'd like to include images to show how the pipeline works, here is how to include an image: 

![alt text][image1]

![alt text][image2]

![alt text][image3]

![alt text][image4]

![alt text][image5]

![alt text][image6]


### 2. Identify potential shortcomings with your current pipeline


One potential shortcoming would be what would happen when ... 

Another shortcoming could be ...


### 3. Suggest possible improvements to your pipeline

A possible improvement would be to ...

Another potential improvement could be to ...
