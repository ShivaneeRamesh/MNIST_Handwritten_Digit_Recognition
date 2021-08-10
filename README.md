# MNIST_Handwritten_Digit_Recognition
This is a MNIST handwritten digit classification problem - a standard dataset used in computer vision and deep learning.
Where the model is trained to predict  images of hand writen digits from 0-9.
I created a neural network for image classification from scratch . And then I trained the model.
Finally ,using OpenCV I displayed images and printed traget along with the prediction of the model.

Neural Network architecture:
Two hidden layers with 128 and 64 neurons respectively
Activation function for hidden layer:Relu
Output layer with 10 neurons
Activation function : Softmax
Loss:sparse_categorical_crossentropy
Learning rate of the model: 0.06
Batch_size:50
No of epochs:10
Overall Accuracy of 97.3%.

Libraries used: Tensorflow, Keras, OpenCV, Numpy.
