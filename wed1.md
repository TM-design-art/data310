# Responses for 7/7/21

##From the Preprocess the data section of the script, modify the training image to produce three new images.

###New Image #1
-[New Image 1](NewImage1.md)

###New Image #2
-[New Image 2](NewImage2.md)

###New Image #3
-[New Image 3]()

##Under the Make predictions section, present the array of predictions for an image from the test set other than the one given in the example script.

probability_model = tf.keras.Sequential([model, tf.keras.layers.Softmax()])

predictions = probability_model.predict(test_images)

predictions[1]

array([7.1652730e-06, 5.0723611e-15, 9.9805683e-01, 7.4160178e-10,
6.1433221e-04, 2.4728529e-16, 1.3216519e-03, 4.8570981e-22,
2.7355423e-10, 1.1303254e-15], dtype=float32)

###What does this array represent?


