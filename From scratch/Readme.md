# Neural Network from Scratch for MNIST
This repository contains a neural network I built from scratch using Python and NumPy to classify handwritten digits from the MNIST dataset. The goal was to gain a deeper understanding of how neural networks work by implementing one from the ground up.

# Overview
I built this neural network without using any frameworks like TensorFlow or PyTorch, just plain Python and NumPy. It was a challenge, but it helped me understand forward propagation, backpropagation, and gradient descent in a much deeper way.

# Architecture
Input Layer: 784 neurons (28x28 pixels)  
Hidden Layer 1: 64 neurons, ReLU activation  
Hidden Layer 2: 32 neurons, ReLU activation  
Output Layer: 10 neurons (for digits 0-9), Softmax activation  

# Requirements
NumPy: For matrix operations
Pandas: For loading the dataset
Matplotlib: For visualizing digits

# Results
After training for 500 iterations with a learning rate of 0.1, the network achieves around 90% accuracy on the test set.

# Why I Built This
I wanted to learn how neural networks work at a low level by implementing everything manually. It was a great learning experience, especially when it came to understanding how the math behind the network translates into code.
