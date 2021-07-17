## Using the script you produced with the Higgs Dataset answer the following questions.

### Describe the dataset. What type of variable is the target? How many features are being used? How many observations are in the training dataset? How many are used in the validation set?

The Higgs Dataset is used as a classification problem that focuses on distinguishing between a signal process that produces Higgs bosons and a background process that does not. The data for the Higgs Dataset has been produced from Monte Carlo simulations. The dataset contains 11,000,000 examples. The target class is binary. In addition, it is a categorical type of variable. There are 28 features being used. In addition, the first 1,000 observations are used in the validation set. The next 10,000 observations are used in the training dataset. 

### How did each of the four models perform (tiny, small, medium and large)? Which of the four models performed the best? Which ones performed the worst? Why in your estimation did certain models perform better? Produce a plot that illustrates and compares all four models.

![img_43.png](img_43.png)


### In this exercise you manually applied a 3x3 array as a filter to an image of two people ascending an outdoor staircase. Modify the existing filter and if needed the associated weight in order to apply your new filters to the image 3 times.

### Plot each result, upload them to your response, and describe how each filter transformed the existing image as it convolved through the original array and reduced the object size. 

filter = [ [-1, -1, -1], [-1, -1, -1], [-1, -1, 8]]

weight  = 1

![img_33.png](img_33.png)

After iterating over the image, leaving a 1 pixel margin, multiplying out each of the neighbors of the current pixel by the value defined in the filter, the filter transform the existing image to have a strong set of both vertical and horizontal lines.

filter = [ [1, 0, 0], [0, 0, 0], [0, 0, -1]]

weight = 1

![img_34.png](img_34.png)

After iterating over the image, leaving a 1 pixel margin, multiplying out each of the neighbors of the current pixel by the value defined in the filter, the filter transform the existing image to have a weak set of both vertical and horizontal lines. 

filter = [ [3, -3, 0], [3, -3, 0], [3, -3, 0]]

weight = 1

![img_35.png](img_35.png)

After iterating over the image, leaving a 1 pixel margin, multiplying out each of the neighbors of the current pixel by the value defined in the filter, the filter transform the existing image to have a predominantly strong set of vertical lines. In addition, this change causses the image to have a weaker set of horizontal lines in comparison to the strong vertical lines.

### What are you functionally accomplishing as you apply the filter to your original array? Why is the application of a convolving filter to an image useful for computer vision? 

When applying the filter to my original array, I am scanning every pixel in the image, looking at its neighboring pixels, and multiplying out the values of these pixels by the equivalent weights in a filter. To clarify, a convolution is a filter that passes over an image, processing it, and extracting features that show a commonality in the image. Also, computer vision is an interdisciplinary scientific field that deals with how computers can gain high-level understanding from digital images or videos. Computers start to gain high-level understanding from digital images or videos through convolution helping them extract features that show a commonality in the image. 

### Another useful method is pooling. Apply a 2x2 filter to one of your convolved images, and plot the result. In effect what have you accomplished by applying this filter? Does there seem to be a logic (i.e. maximizing, averaging or minimizing values?) associated with the pooling filter provided in the example exercise (convolutions & pooling)? Did the resulting image increase in size or decrease? Why would this method be useful?
I applied a 2x2 filter to my convolved image with the filter = [ [3, -3, 0], [3, -3, 0], [3, -3, 0]]
and the weight = 1.

![img_41.png](img_41.png)

By applying this 2x2 filter from the example exercise, I have maintained the extracted features while reducing the image to 1/4 the size of the original image. 
These extracted features include a strong set of vertical lines and a weaker set of horizontal lines. 
Therefore, I am both reducing the overall amount of information in the image and maintaining the detected features. 
When using the 2x2 pooling filter provided in the example exercise, we are using max pooling. Max pooling involves iterating over an image, looking at a pixel and its immediate neighbors, taking the largest of them, and loading this largest into the new image. 
Overall, this method would be useful, because pooling reducing image size and maintaining features of images will allow code using these images to be more efficient. The code will be more efficient due to data from the images now being classified based on features rather than raw pixels. 

#### Finally, review the following images from class and then convolve the 3x3 filter over the 9x9 matrix and provide the resulting matrix.

![img_40.png](img_40.png)