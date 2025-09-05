# Activation Functions in Python

## Overview
This repository contains implementations of common **activation functions** used in deep learning, written in **Python**. Activation functions are mathematical operations applied to neurons in neural networks to introduce **non-linearity**, allowing the model to learn complex patterns.

The following activation functions are included:

1. **Sigmoid**
2. **Tanh (Hyperbolic Tangent)**
3. **ReLU (Rectified Linear Unit)**
4. **Leaky ReLU**

Each function includes **example outputs** and **visual plots** for better understanding.

---

## Functions

### 1. Sigmoid
- **Formula:** `σ(x) = 1 / (1 + e^(-x))`
- **Output range:** (0, 1)
- **Use case:** Binary classification problems.
- **Example:**
```python
sigmoid(1)  # Output: 0.731
sigmoid(-56) # Output: ~0
2. Tanh
Formula: tanh(x) = (e^x - e^-x) / (e^x + e^-x)

Output range: (-1, 1)

Use case: Hidden layers in deep learning networks.

Example:

python
Copy code
tanh(1)   # Output: 0.761
tanh(-56) # Output: ~-1
3. ReLU
Formula: ReLU(x) = max(0, x)

Output range: [0, ∞)

Use case: Hidden layers in most modern networks.

Example:

python
Copy code
relu(-7)  # Output: 0
relu(8)   # Output: 8
4. Leaky ReLU
Formula: LeakyReLU(x) = x if x>0 else 0.1*x

Output range: (-∞, ∞)

Use case: Avoids "dying ReLU" problem.

Example:

python
Copy code
leaky_relu(-100) # Output: -10
leaky_relu(8)    # Output: 8
Usage
Clone this repository:

bash
Copy code
git clone https://github.com/yourusername/activation-functions-python.git
Run the Python script:

bash
Copy code
python activation_functions.py
See the outputs of all activation functions for sample inputs and the plots.

Author

Zara Irfan – passionate about Deep Learning and Python programming.


