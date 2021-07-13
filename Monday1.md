# Informal Responses for Monday 7/12/21

### Which of the two models produces a better loss metric (see this link for an explanation of the loss function). Produce a plot that supports your answer. 

For the first set of models, I used highway-mpg as target and num-of-cylinders, engine-size, horsepower, curb-weight as the features. When using multi-class linear regression, the mean absolute error for this model was around 2.051928. When using multi-class DNN regression, the mean absolute error for this model was around 3.362609. Due to the model created by the usage of multi-class linear regression having a lower mean absolute error, I would say that this model produces a better loss metric.

#### Graphs for First Set of Models

#### Linear Model

![img_24.png](img_24.png)

#### DNN Model

![img_25.png](img_25.png)

### Return to the remainder of the variables from the dataset and add additional continuous and categorical features with the intent of improving your loss metric. Produce a plot that demonstrates the value of your model. What is the best model your team was able to produce?

### Second Set of Models

For the second set of models, I used highway-mpg as target and num-of-cylinders, engine-size, horsepower, curb-weight, fuel-type, price, wheel-base, fuel-system as the features. When using multi-class linear regression, the mean absolute error for this model was around 3.570920. When using multi-class DNN regression, the mean absolute error for this model was around 2.094814.

#### Linear Model

![img_26.png](img_26.png)

#### DNN Model

![img_27.png](img_27.png)

### Third Set of Models

For the third set of models, I used highway-mpg as target and num-of-cylinders, engine-size, horsepower, curb-weight, num-of-doors, peak-rpm, bore, body style as the features. When using multi-class linear regression, the mean absolute error for this model was around 2.557662. When using multi-class DNN regression, the mean absolute error for this model was around 2.494790.

### Linear Model

![img_30.png](img_30.png)

### DNN Model

![img_29.png](img_29.png)

### Fourth Set of Models

For the fourth set of models, I used highway-mpg as target and num-of-cylinders, engine-size, horsepower, curb-weight, engine location, compression ratio, stroke, aspiration as the features. When using multi-class linear regression, the mean absolute error for this model was around 1.609359. When using multi-class DNN regression, the mean absolute error for this model was around 1.893565.

### Linear model

![img_31.png](img_31.png)

### DNN Model

![img_32.png](img_32.png)

## Overall, the linear model from the fourth set of models had the lowest mean absolute error value. Based on this information, I would say that this is the best model that my team was able to produce. 


