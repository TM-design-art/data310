###Accuracy values of training and testing datasets

After fitting the model by using model.fit(train_images, train_labels, epochs=10) and
dividing the values by 255 to scale the values before processing them through the neural network model,
I calculated the accuracy of the training dataset to be 0.9973166584968567. In addition,
I calculated the accuracy of the testing dataset to be 0.9790999889373779. 

test_loss, test_acc = model.evaluate(test_images,  test_labels, verbose=2)

print('\nTest accuracy:', test_acc)

Test accuracy: 0.9790999889373779

train_loss, train_acc = model.evaluate(train_images,  train_labels, verbose=2)

Train accuracy: 0.9973166584968567

print('\nTrain accuracy:', train_acc)
