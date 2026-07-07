# 3-Layer Neural Network from Scratch using NumPy

## Project Overview
This project implements a 3-layer Neural Network from scratch using only NumPy, without using deep learning frameworks like Keras or TensorFlow.

The model is trained on the XOR dataset using:
- Forward Propagation
- Backpropagation
- Gradient Descent
- Sigmoid Activation Function
- Mean Squared Error (MSE) Loss

## Technologies Used
- Python
- NumPy
- Google Colab
- GitHub

## Dataset

Input (X):

```python
X = [
    [0, 0],
    [0, 1],
    [1, 0],
    [1, 1]
]
```

Output (y):

```python
y = [
    [0],
    [1],
    [1],
    [0]
]
```

## Neural Network Architecture

- Input Layer: 2 neurons
- Hidden Layer: 4 neurons
- Output Layer: 1 neuron
- Activation Function: Sigmoid

## Features

- Pure NumPy implementation
- Manual weight initialization
- Forward propagation
- Backpropagation
- Gradient descent optimization
- XOR classification
- Loss calculation using Mean Squared Error

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/3-Layer-Neural-Network-NumPy.git
```

2. Open the notebook in Google Colab or Jupyter Notebook.

3. Run all cells.

## Expected Output

The loss decreases over training epochs, and the final predictions become close to the expected XOR outputs.

Example:

```
Final Predictions:
[[0.01]
 [0.99]
 [0.99]
 [0.01]]
```

Rounded Predictions:

```
[[0]
 [1]
 [1]
 [0]]
```

#
