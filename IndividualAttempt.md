## Provide plots that describe the training and validation loss and accuracy. Interpret the plots. How is this model performing?

Training loss decreases with each epoch, and training accuracy increases with each epoch.
These changes are caused by using a gradient descent optimization. The usage of a gradient descent optimization minimizes the desired quantity on every iteration. While the validation loss undergoes a similar change, the validation accuracy seems to slightly peak before the training accuracy. Therefore, there could be slight overfitting.
Overfitting means that the model does better on the training data than on new data.

![img_14.png](img_14.png)
![img_15.png](img_15.png)

## Export the model and print the 
