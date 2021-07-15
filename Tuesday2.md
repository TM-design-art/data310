### In this exercise you manually applied a 3x3 array as a filter to an image of two people ascending an outdoor staircase. Modify the existing filter and if needed the associated weight in order to apply your new filters to the image 3 times.

###Plot each result, upload them to your response, and describe how each filter transformed the existing image as it convolved through the original array and reduced the object size. 

filter = [ [-1, -1, -1], [-1, -1, -1], [-1, -1, 8]]

weight  = 1

![img_33.png](img_33.png)

filter = [ [1, 0, 0], [0, 0, 0], [0, 0, -1]]

weight = 1

![img_34.png](img_34.png)

filter = [ [3, -3, 0], [3, -3, 0], [3, -3, 0]]

weight = 1

![img_35.png](img_35.png)

###What are you functionally accomplishing as you apply the filter to your original array? Why is the application of a convolving filter to an image useful for computer vision? 

###Stretch goal: instead of using the misc.ascent() image from scipy, can you apply three filters and weights to your own selected image? Describe your results.

#### 