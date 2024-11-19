Description
This project implements a neural network model for binary classification using TensorFlow. The model is trained on a dataset with two features and performs classification using two dense layers with ReLU activation. The output layer uses softmax activation for binary classification.

Optimizers Used:
Adagrad: An adaptive gradient algorithm that adjusts the learning rate for each parameter based on the gradient history.
Adam: A popular optimization algorithm that combines the advantages of both Adagrad and RMSProp, maintaining adaptive learning rates and momentum.
RMSProp: An optimizer that adapts the learning rate for each parameter by considering the moving average of the squared gradients.
Purpose:
The goal of this project is to compare the performance of different optimizers (Adagrad, Adam, and RMSProp) in training a neural network model. The code includes training, evaluation, and generation of confusion matrices for both the training and testing sets. It also visualizes the confusion matrices to help assess model performance and compare the output of each optimizer.
