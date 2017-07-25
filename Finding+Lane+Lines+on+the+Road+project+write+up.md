

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


```python
2. Identify potential shortcomings with your current pipeline:
    1 -  the camera is placed in fixed place
    2-   any line in the region I assumed will be lane line
```


```python
3. Suggest possible improvements to your pipeline:
    1-tuning the parameters more than that
    2-choosing region of interset depend on the road
```


```python
this is link of my notebook code
http://localhost:8889/notebooks/Finding%20Lane%20Lines%20on%20the%20Road%20project.ipynb#
```
