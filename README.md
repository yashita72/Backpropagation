# Backpropagation

This repository contains implementations of **Backpropagation in Neural Networks** using:

- Regression from Scratch
- Classification from Scratch
- Regression using Keras/TensorFlow

The project is created for understanding how neural networks learn through forward propagation, loss calculation, backpropagation, and weight updates.

---

# Files Included

## 1. backpropagation-regression.ipynb

Implementation of backpropagation for a regression problem from scratch using NumPy.

### Features
- Manual forward propagation
- Mean Squared Error (MSE) loss
- Manual gradient calculation
- Weight and bias updates
- Epoch implementation

### Concepts Used
- Linear activation
- Gradient Descent
- Regression Neural Network

---

## 2. backpropagation-classification.ipynb

Implementation of backpropagation for binary classification from scratch using NumPy.

### Features
- Sigmoid activation
- Binary Cross Entropy Loss
- Manual backpropagation
- Classification prediction
- Epoch training loop

### Concepts Used
- Binary Classification
- Sigmoid Function
- Cross Entropy Loss
- Gradient Descent

---

## 3. keras-regression.ipynb

Regression Neural Network implemented using TensorFlow/Keras.

### Features
- Sequential model
- Dense layers
- Adam optimizer
- Mean Squared Error loss
- Automatic backpropagation

### Concepts Used
- Deep Learning with Keras
- Neural Network Training
- Optimizers
- Model Compilation

---

# Technologies Used

- Python
- NumPy
- Pandas
- TensorFlow
- Keras
- Google Colab

---

# Neural Network Architecture

## Regression

```text
Input Layer (2)
       ↓
Hidden Layer (2)
       ↓
Output Layer (1)
```

## Classification

```text
Input Layer (2)
       ↓
Hidden Layer (2)
       ↓
Output Layer (1 - Sigmoid)
```

---

# Loss Functions

## Regression Loss

Mean Squared Error:

```math
Loss = (y - \hat{y})^2
```

## Classification Loss

Binary Cross Entropy:

```math
Loss = -y\log(\hat{y}) - (1-y)\log(1-\hat{y})
```

---

# Learning Outcomes

This project helps in understanding:

- Forward Propagation
- Backpropagation
- Weight Initialization
- Gradient Descent
- Activation Functions
- Neural Network Training
- Regression vs Classification

---

# Author

Yashita

GitHub: https://github.com/yashita72# Backpropagation
