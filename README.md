Project: Image Classification with Convolutional Neural Networks (CNN)

This project demonstrates how to perform image classification using a Convolutional Neural Network (CNN). The task is to classify images of pizza and not pizza using a CNN model implemented in TensorFlow.

Requirements:

Python 3.x
TensorFlow 2.x
numpy
matplotlib
OpenCV
PIL
sklearn
kagglehub

Project Overview:
In this project, we will use a CNN to classify images from the "Pizza vs. Not Pizza" dataset. The dataset is sourced from Kaggle and contains two categories:
Pizza
Not Pizza (which includes images of other items that are not pizza)

Project Workflow:

Dataset Download: The project starts by downloading the dataset from Kaggle using the kagglehub API.

Image Preprocessing: The images are resized to a uniform size (180x180) and normalized.

Model Architecture: A simple CNN model is built using TensorFlow/Keras.

Model Training: The model is trained using 80% of the data and tested on 20% of the data.

Evaluation: After training, the model is evaluated on the test set, and its accuracy and loss are plotted.

Predictions: The model is used to predict classes for new test images.

