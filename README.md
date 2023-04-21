# Image-Classification-with-MNIST-Convnet

Image classification is indeed a subfield of computer vision which involves training neural networks to recognize and categorize images into predefined classes. This has applications in various fields such as object detection, facial recognition, medical diagnosis, and even autonomous driving.

Image classification has become an essential component of many applications, including search engines, social media platforms, and e-commerce sites. As the field continues to advance, it has the potential to impact many industries and change the way we interact with technology.


<p align="center">
  <img src="https://user-images.githubusercontent.com/71633926/233614356-d5b785db-43ef-480f-92f4-0cb17c288508.png" />
</p>
 MNIST is a database of handwritten digits. It is the most commonly used dataset for learning Image Recognition. It is labelled in the sense that each image of handwritten digit has the corresponding numeral value attached to it. This helps our Algorithm/Neural Network to learn which image stands for which number(0-9) and to learn hidden patterns in human writing.

<h2>Methodology:</h2>
We will use the Keras library to implement a ConvNet for image classification with the MNIST dataset. The ConvNet architecture we will use consists of multiple layers, including convolutional layers, pooling layers, and fully connected layers. The convolutional layers are responsible for extracting features from the input images, while the pooling layers reduce the dimensionality of the feature maps. Finally, the fully connected layers classify the features.

The following is the architecture of our ConvNet:

Convolutional layer with 32 filters of size 3x3
Max pooling layer with pool size 2x2
Convolutional layer with 64 filters of size 3x3
Max pooling layer with pool size 2x2
Flatten layer
Fully connected layer with 128 units and ReLU activation
Dropout layer with rate 0.5
Output layer with 10 units and softmax activation
The model is compiled using the categorical cross-entropy loss function and the Adam optimizer. We train the model for 10 epochs with a batch size of 128.

<h2>Results:</h2>
After training the model, we evaluate its performance on the test set, which consists of 10,000 images. The model achieves an accuracy of 99.25% on the test set, which is a good performance. We can also visualize the confusion matrix to see which digits are most often confused with each other. The confusion matrix shows that the most common errors are between 4s and 9s, as well as between 3s and 8s.

<h2>Conclusion:</h2>
In this report, we explored the use of a ConvNet for image classification with the MNIST dataset. The ConvNet architecture we used consists of multiple layers, including convolutional layers, pooling layers, and fully connected layers. After training the model, we achieved an accuracy of 99.25% on the test set, which is a good performance. The model can be further improved by tuning the hyperparameters or by using a more advanced architecture. Overall, the ConvNet is a powerful algorithm for image classification tasks and can be used in a wide range of applications.
