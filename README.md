# Micrograd from Scratch 🧠

A lightweight, scalar-valued **Automatic Differentiation (Autograd) engine** and a simple **Neural Network library** implemented from scratch in Python, inspired by Andrej Karpathy's `micrograd`.

## 📌 Project Overview
This project demonstrates the core fundamentals of how deep learning frameworks (like PyTorch or TensorFlow) compute gradients using Backpropagation over a Dynamic Computation Graph.

### Key Features:
* **Autograd Engine (`engine.py`)**: Implemented `Value` class supporting scalar operations (`+`, `*`, `**`, `relu`, `tanh`, `exp`) and topological sort for reverse-mode automatic differentiation.
* **Neural Network Module (`nn.py`)**: Built-in implementations for `Neuron`, `Layer`, and `MLP` (Multi-Layer Perceptron).
* **Jupyter Notebook Demos**: Visual traces of computation graphs and step-by-step training on simple datasets.

## 🛠️ Project Structure
```text
neturalnetworks/
├── engine.py              # Autograd engine (Value class)
├── nn.py                  # Neural network components (Neuron, Layer, MLP)
├── trace_graph.ipynb      # Graph visualization notebook
├── microgradjupiter/      # Interactive Jupyter demos
│   ├── enginedemo.ipynb   # Autograd engine verification
│   └── mlpdemo.ipynb      # Training an MLP model
├── .gitignore             # Git ignore rules
└── README.md              # Project documentation