# mlp-from-scratch
This repository contains a basic implementation of a **2-layer Multi-Layer Perceptron (MLP)** from scratch using **NumPy**. The network is designed for regression tasks using **Mean Squared Error (MSE)** as the loss function.

## Features

- Fully connected **2-layer neural network** (input → hidden → output)  
- **Sigmoid activation** for the hidden layer  
- Implements **feedforward** and **backpropagation** manually  
- Supports **mini-batch gradient descent**  
- Tracks **loss history** during training  

---

## Usage

### Import and initialize

```python
from mlp import MLP  # assuming the class is saved in mlp.py (python format, not jupyter-notebook)
import numpy as np

# Example: 3 input features, 4 hidden units
model = MLP(input_num=3, hidden_num=4)
model.fit(X,y)
