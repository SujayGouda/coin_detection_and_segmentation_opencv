# coin_detection_and_segmentation_opencv
For an given Image: 
1. Pre-processes the image using OpenCV
2. Applies Hough Transformation to detect contours (Circles)
3. Labels the coins with circles and serial numbers 
4. If coins are apart from each other, then segments the coins by drawing a vertical line

### Libraries:
OpenCV
Numpy
Matplotlib 
itertools

## Preview:
### Test input image:

![alt text](https://github.com/SujayGouda/coin_detection_and_segmentation_opencv/blob/main/test_input/test1.jpg?raw=true)


### 1. Detects the number of coins in the image and Labels them with serial numbers 

![alt text](https://github.com/SujayGouda/coin_detection_and_segmentation_opencv/blob/main/sample_output/out1.png?raw=true)


### 2. (Segmentation) Draws a vertical line in between coins 

![alt text](https://github.com/SujayGouda/coin_detection_and_segmentation_opencv/blob/main/sample_output/test1.jpg?raw=true)
