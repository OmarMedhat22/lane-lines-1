# lane-lines-1



```python
The goals / steps of this project are the following:
I begin with writing the code 
1- Color Selection
2-Canny Edge Detection
3-Hough Transform
I used functions to make the code more readable
```


```python
Reflecton :
```


```python

1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function
My pipeline consisted of  steps:
Firstly, I converted the image to grayscale 
secondly , I tunned the paramaters (low_threshold ,high_threshold )
then i tunned the another paramters (rho ,theta,threshold,min_line_length,max_line_gap).
thirdly , I made a  draw lines on a blank image
  and I add a weighted function by using my orignal image and my iblank image with red lines 
```
