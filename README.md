# Fashion-MNIST Image Classification using CNN

## About the Project

I worked on this project to understand how image classification works using a Convolutional Neural Network (CNN).

I used the Fashion-MNIST dataset and built a CNN model using TensorFlow and Keras to classify images into different clothing categories.

## Dataset

The Fashion-MNIST dataset contains 28 × 28 grayscale images belonging to 10 different clothing categories.

The dataset contains:
- 60,000 training images
- 10,000 testing images

## What I Did

- Loaded the Fashion-MNIST dataset using TensorFlow/Keras
- Explored sample images and their classes
- Normalized the image pixel values
- Reshaped the images for CNN input
- Built a CNN using Conv2D and MaxPooling2D layers
- Added Flatten and Dense layers for classification
- Trained the model for 5 epochs
- Evaluated the model on the test dataset

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Jupyter Notebook

## Model

The CNN model consists of:
- 3 Convolutional layers
- Max Pooling layers
- Flatten layer
- Dense layer with 128 neurons
- Output layer with 10 classes

## Result

The model was trained and evaluated on the Fashion-MNIST dataset.

**Test Accuracy:** 90% 

## What I Learned

This project helped me understand the basic workflow of image classification using CNNs, including image preprocessing, building a neural network, training the model and evaluating its performance.
