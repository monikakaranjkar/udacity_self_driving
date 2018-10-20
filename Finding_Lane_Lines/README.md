# **Finding Lane Lines on the Road** 
In this project you will detect lane lines in images using Python and OpenCV.
---
The goals / steps of this project are the following:
---
1)Detect lanes from a color image.
---
2)validate algorithm with set of images 
---
3)validate algorithm with video input 
---
4)save the output video
---

[//]: # (Image References)

[image1]: ./results/gray.png "Grayscale"
[image2]: ./results/blur_gray.png "blur"
[image3]: ./results/edges.png "Canny Edge"
[image4]: ./results/final_output.png "hough line"



---
# Pipeline

Consisted of below steps.
---
1-Color to Gray
![alt text][image1]
---
2-Blurring
![alt text][image2]
---
3-Canny edge detector
![alt text][image3]
---
4-Hough tranform
![alt text][image4]
---


# Possible Improvements

Possible improvements are:

1) Edge detection with recent state of art algorithms which can give better result.
2) Detecting lanes in curvy roads.
3) Testing with more complex scenarios like different lighting conditions, more objects on road etc.
