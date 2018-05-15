# **Finding Lane Lines on the Road** 
**Finding Lane Lines on the Road**
In this project, we will identify lane lines on the road by run an algorithm on a series of individual images, and then apply the algorithm to a video stream (just a series of images), then draw just one line for the left side of the lane, and one for the right.

### Reflection
### 1. Project pipeline description:
We will follow the following steps to detect the line segments in the image, then average/extrapolate them and draw them onto the image for display (as below):
1. Read the Image
2. Convert image to gray scale (grayscaling)
3. Apply gaussian smoothing filter
4. Canny Edge Detection
5. region of interest selection
6. Hough Tranform line detection

### 2. Potential shortcomings with the current pipeline:

Curved lane lines are and identified precisely. 


### 3. Suggest possible improvements to the pipeline:

Improve the Hough transform in the algorithm to detect curved lane lines besides the normal straight lines.
