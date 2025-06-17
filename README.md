# Churn-Prediction
Churn Prediction using Artificial Neural Network (ANN)
This project implements a customer churn prediction model using an Artificial Neural Network (ANN) with Keras and TensorFlow. The model predicts whether a customer is likely to churn (leave) based on various input features.

Model Architecture
The ANN model is built with the following layers:

Input Layer:

- Dense layer with 11 neurons (matching input dimension)

- ReLU activation function

- Input dimension: 11 features

Hidden Layer:

- Dense layer with 11 neurons

- ReLU activation function

Output Layer:

- Dense layer with 1 neuron (binary classification)

- Sigmoid activation function

Model Configuration
The model is compiled with:

- Loss function: Binary crossentropy (suitable for binary classification)

- Optimizer: Adam (adaptive moment estimation)

- Metrics: Accuracy (to evaluate model performance)

## Requirements
To run this project, you need the following Python libraries:

- TensorFlow (>=2.0)

- Keras

- NumPy

- Pandas

- Scikit-learn (for data preprocessing and evaluation)
