## Using the Classify structured data using Keras Preprocessing Layers you prepared for today's class as a model example, train, validate and test a model that has wealth class as the target as follows.

### Import the dataset country_persons.csv to your PyCharm environment

### Initially set the target to the least wealthy class, 1 in this case, and set all other wealth class outcomes to 0 (2,3,4 & 5)

### Train, validate and test your model

### Interpret and analyze your results. Did the model performance exhibit a particular trend?

For the first set of models, I dropped the unit, hhid, and pnmbr columns from the data frame of the country persons csv file. I used the weights feature, size feature, and age feature as numeric features. Also, I used the gender feature, education feature, location feature, potable feature, toilet feature, electric feature, car feature, cook feature as categorical features. For the model focusing on wealth class 1, the testing accuracy is around 0.7881. For the model focusing on wealth class 2, the testing accuracy is around 0.7370. For the model focusing on wealth class 3, the testing accuracy is around 0.7981. For the model focusing on wealth class 4, the testing accuracy is around 0.8905. For the model focusing on wealth class 5, the testing accuracy is around 0.9571. 

For the second of models, I did the same actions from the first set of models and added another dense layer. For the model focusing on wealth class 1, the testing accuracy is around 0.7911. For the model focusing on wealth class 2, the testing accuracy is around 0.7380. For the model focusing on wealth class 3, the testing accuracy is around 0.7942. For the model focusing on wealth class 4, the testing accuracy is around 0.8893. For the model focusing on wealth class 5, the testing accuracy is around 0.9607. 

For the third set of models, I did the same actions from the first set of models. However, I changed the optimizer from adam to SGD. To clarify, Adam optimization is a stochastic gradient descent method that involves the adaptive estimation of first-order and second-order moments. SGD optimization is a gradient descent (with momentum) optimizer. For the model focusing on wealth class 1, the testing accuracy is around 0.7530. For the model focusing on wealth class 2, the testing accuracy is around 0.7358. For the model focusing on wealth class 3, the testing accuracy is around 0.7892. For the model focusing on wealth class 4, the testing accuracy is around 0.8784. For the model focusing on wealth class 5, the testing accuracy is around 0.9178. 

For all sets of models, I used 10 epochs when training the models.

Overall, when changing the focus from wealth class 1 to class 2, the testing accuracy for all sets of models seems to decrease. For the changes in focus from wealth classes 2 to 3, wealth classes 3 to 4, wealth classes 4 to 5, the testing accuracy for all sets of models increases. For the most part, the second set of models has greater testing accuracy values than the first set of models. Also, the first set of models seems to always have higher testing accuracy values than the third set of models. Based on this information, adding another dense layer seems to cause testing accuracy values to increase. Changing the optimizer to SGD seems to cause the testing accuracy values to decrease. 