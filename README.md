<h1>
<br>CIFAR_10_Image_Classification
</h1>

---

## 📒 Table of Contents
- [📒 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [📂 Project Structure](#-project-structure)
- [🔎 Details of Codes](#-details-of-codes)
- [🚀 Getting Started](#-getting-started)
- [🤝 Collaborators](#-collaborators)


---
## 📍 Overview

This project is one of the Computational Intelligence course projects in the spring of 2023, and it includes code related to training neural networks with gradient descent, training neural network using neuroevolution, Neural Architecture Search (NAS), and Self-Organizing Maps (SOM). The core functionalities of the project are image classification tasks using the [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) dataset. The purpose of the project is to explore and compare different approaches and techniques for improving the accuracy and efficiency of image classification models.

---


## 📂 Project Structure

 * [README.md](./README.md)
 * [Codes](./Codes)
   * [NAS.ipynb](./Codes/NAS.ipynb)
   * [SOM.ipynb](./Codes/SOM.ipynb)
   * [Training_Neural_Network.ipynb](./Codes/Training_Neural_Network.ipynb)
   * [Training_Using_Neuro_Evolution.ipynb](./Codes/Training_Using_Neuro_Evolution.ipynb)
  
---

## 🔎 Details of Codes

### [Training_Neural_Network](./Codes/Training_Neural_Network.ipynb)
Gradient descent is an optimization algorithm commonly used for training neural networks. It iteratively adjusts the parameters of the neural network (such as weights and biases) to minimize a defined loss function. By computing gradients and updating the parameters in the direction of steepest descent, gradient descent helps the neural network gradually improve its performance over time.

### [Training_Using_Neuro_Evolution](./Codes/Training_Using_Neuro_Evolution.ipynb)
Neuro-Evolution combines neural networks and evolutionary algorithms to optimize the parameters (such as weights and biases). It involves evolving a population of neural networks through processes such as mutation, crossover, and selection, similar to how genetic algorithms work in evolutionary computation for improved performance on image classification tasks.

### [NAS](./Codes/NAS.ipynb)
Neural architecture search is a technique used to automatically discover the architecture of a neural network that performs well on a given task. It involves searching through a large space of possible network architectures with evolutionary algorithms to find the most suitable one.

### [SOM](./Codes/SOM.ipynb)
Self-Organizing Maps (SOM) is an unsupervised learning algorithm used for clustering and visualization of high-dimensional data. It maps the input data onto a lower-dimensional grid, preserving the topological relationships between the data points.


---
## 🚀 Getting Started

### ✔️ Requirements

Before you begin, ensure that you have the packages in `requirements.txt` installed.

### 📦 Installation

1. Clone the CIFAR_10_Image_Classification repository:
```sh
git clone https://github.com/kianmajl/CIFAR_10_Image_Classification.git
```

2. Change to the project directory:
```sh
cd CIFAR_10_Image_Classification
```

3. Install the dependencies:
```sh
pip install -r requirements.txt
```

### 🎮 Using CIFAR_10_Image_Classification

Now you can train neural network with [gradient descent](./Codes/Training_Neural_Network.ipynb) or [neuro evolution](./Codes/Training_Using_Neuro_Evolution.ipynb), find the best architecture for neural network with [NAS](./Codes/NAS.ipynb), and classify images with the method you want.

---
## 🤝 Collaborators
[Kian Majlessi](https://github.com/kianmajl) and [Audrina Ebrahimi](https://github.com/audrina-ebrahimi)
