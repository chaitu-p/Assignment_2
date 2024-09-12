# Assignment_2

# Iris Classification Model

## Overview
This project implements a simple neural network for classifying iris flower species using the classic Iris dataset. The model is built using TensorFlow and Keras.

## Dataset
The dataset consists of 150 samples of iris flowers, each described by 4 features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

There are 3 target classes:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

## Model
The model is a feed-forward neural network with the following architecture:
- Input layer with 64 neurons
- Hidden layer with 64 neurons and ReLU activation
- Output layer with 3 neurons and softmax activation for multi-class classification.

## Results
The final test accuracy is approximately 97%. See the classification report for more details.

## Instructions
1. Install the required libraries:
   ```bash
   pip install numpy pandas scikit-learn tensorflow
