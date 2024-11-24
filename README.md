# Binary Classification with Neural Networks

## Description
This project implements a neural network model for **binary classification** using **TensorFlow**.  
The model is trained on a dataset with two features and performs classification using:  
- **Two dense layers** with **ReLU activation**.  
- An **output layer** with **softmax activation** for binary classification.

## Optimizers Used
### 1. **Adagrad**
   - An adaptive gradient algorithm that adjusts the learning rate for each parameter based on the gradient history.  

### 2. **Adam**
   - A popular optimization algorithm that combines the advantages of both Adagrad and RMSProp.  
   - Maintains **adaptive learning rates** and **momentum** for efficient convergence.  

### 3. **RMSProp**
   - Adapts the learning rate for each parameter by considering the **moving average** of the squared gradients.

## Purpose
The goal of this project is to **compare the performance of different optimizers** (Adagrad, Adam, and RMSProp) in training a neural network model.  

Key features include:  
- **Training and evaluation** of the model.  
- Generation of **confusion matrices** for both the training and testing sets.  
- Visualization of the confusion matrices to:  
  - Assess model performance.  
  - Compare the output of each optimizer.
