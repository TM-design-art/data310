i = 9998

plt.figure(figsize=(6,3))

plt.subplot(1,2,1)

plot_image(i, predictions[i], test_labels, test_images)

plt.subplot(1,2,2)

plot_value_array(i, predictions[i],  test_labels)

plt.show()

![img_5.png](img_5.png)