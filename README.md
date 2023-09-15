# Neural Network 
![NN gif](NN.gif)


This repository contains a Python code implementation of a neural network from scratch, with various experiments and analyses. The code is designed to help you understand the fundamentals of neural networks, including different architectures, activation functions, and optimization techniques.

## Table of Contents
1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
3. [Generating Datasets](#generating-datasets)
4. [Neural Network Architecture](#neural-network-architecture)
5. [Activation Functions](#activation-functions)
6. [Mini-Batch Gradient Descent](#mini-batch-gradient-descent)
7. [Learning Rate Schedule](#learning-rate-schedule)
8. [Experimentation](#experimentation)
   - [Part One](#part-one)
   - [Part Two](#part-two)
   - [Part Three](#part-three)
   - [Part Four](#part-four)
   - [Part Five](#part-five)
   - [Part Six](#part-six)
   - [Part Seven](#part-seven)
9. [Conclusion](#conclusion)

---

## Introduction<a name="introduction"></a>

This project provides a Python implementation of a neural network. The code is organized into different parts, each exploring various aspects of neural networks, including architecture, activation functions, optimization techniques, and dataset exploration.

---

## Getting Started<a name="getting-started"></a>

Before running the code, make sure you have the following libraries installed:
- NumPy
- scikit-learn
- Matplotlib

You can install these libraries using pip:

```
pip install numpy scikit-learn matplotlib
```
Once you have the required libraries, you can run the code in your favorite Python environment or Jupyter Notebook.

## Generating Datasets<a name="generating-datasets"></a>

We start by generating synthetic datasets using scikit-learn to experiment with various neural network configurations. Two datasets are used:

- Moons Dataset
- Blobs Dataset (Part 6)

The datasets are plotted for visualization.

## Neural Network Architecture<a name="neural-network-architecture"></a>

We define a neural network with the following architecture:

- Input layer: 2 neurons
- Hidden layers: Variable size (Part 2)
- Output layer: 2 neurons (Part 6)

The neural network is trained using gradient descent with optional regularization.

## Activation Functions<a name="activation-functions"></a>

We explore two activation functions:

- Sigmoid
- Tanh (Part 5)

We also implement their derivative functions for backpropagation.

## Mini-Batch Gradient Descent<a name="mini-batch-gradient-descent"></a>

We compare the performance of mini-batch gradient descent with batch gradient descent (Part 3).

## Learning Rate Schedule<a name="learning-rate-schedule"></a>

We implement a learning rate schedule that decreases the learning rate after each iteration (Part 4).

## Experimentation<a name="experimentation"></a>

In this section, we conduct various experiments and analyze the results.

### Part One<a name="part-one"></a>
We train the neural network with a hidden layer of size 3 and plot the decision boundary.

### Part Two<a name="part-two"></a>
We vary the hidden layer size and observe the impact on loss and decision boundaries.

### Part Three<a name="part-three"></a>
We implement mini-batch gradient descent and compare it with batch gradient descent.

### Part Four<a name="part-four"></a>
We experiment with a learning rate schedule that decreases the learning rate over time.

### Part Five<a name="part-five"></a>
We introduce the sigmoid activation function and compare it with the tanh activation function.

### Part Six<a name="part-six"></a>
We use a different dataset with three classes (Blobs) and adapt the neural network for multiclass classification.

### Part Seven<a name="part-seven"></a>
We experiment with various hidden layer sizes for multiclass classification.

## Conclusion<a name="conclusion"></a>

Through these experiments, we've gained insights into how different parameters and techniques affect neural network performance. We observed that the choice of architecture, activation functions, and regularization can significantly impact the network's performance. Additionally, mini-batch gradient descent and learning rate schedules can improve training efficiency. Finally, we found an optimal hidden layer size for the multiclass classification task.

Feel free to explore, modify, and extend this code to deepen your understanding of neural networks. Enjoy experimenting and learning!

