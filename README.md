# Multiclass-Classification-with-Fashion-MNIST-Using-Keras-ANN-Only
The goal is to build a multiclass classification model using Keras with TensorFlow backend to classify fashion items from the Fashion MNIST dataset. The dataset contains 28x28 grayscale images of 10 different fashion categories.

Dataset:
Fashion MNIST consists of 70,000 images, where:
60,000 images are for training
10,000 images are for testing
Each image belongs to one of 10 classes:
T-shirt/topTrouserPulloverDressCoatSandalShirtSneakerBagAnkle boot

Loaded the Fashion MNIST dataset using keras.datasets.
Split the data into training and testing sets (0.8,0.2).
Normalize the images so that pixel values are scaled between 0 and 1.
Flatten the 28x28 images into 1D vectors of size 784 (28*28) since we'll be using an Artificial Neural Network (ANN).
Visualize some images with their corresponding labels for reference.
Create an ANN model using Keras Sequential API.
The architecture should include:
An input layer that accepts the flattened 784-dimensional vector.
At least two fully connected (dense) hidden layers with a reasonable number of neurons (e.g., 128, 64 neurons) and ReLU activation.
An output layer with 10 neurons (one for each class) and softmax activation to output probabilities for each class.
