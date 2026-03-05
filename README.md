# Deep Learning Regression: From Scratch to High-Level APIs

This repository contains a comprehensive exploration of 3-layer Deep Neural Networks (DNNs) for non-linear regression. We progress from raw mathematical implementations using **NumPy and Tensor Einsum** to high-level abstractions in **PyTorch Lightning** and **TensorFlow**.

## 📺 Video Walkthrough
[![Project Walkthrough]](https://youtu.be/WDerNwz55gA)

---

## 🚀 Projects Overview

### A) NumPy from Scratch (3-Layer DNN)
* **Description:** A pure NumPy implementation (with `tf.einsum`) of a 3-layer network.
* **Key Features:** Manual backpropagation, chain rule implementation, and 4D plotting of 3-variable non-linear data.
* **Highlights:** Uses `einsum` for optimized matrix operations.
* [View Colab]([https://colab.research.google.com/drive/1xdt5DET1id38VNmUc1Q-F_VVZJ0SyAa_?usp=sharing)

### B) PyTorch from Scratch
* **Description:** Building the 3-layer architecture without `torch.nn.Linear`.
* **Key Features:** Manual weight initialization and gradient descent loop.
* [View Colab](https://colab.research.google.com/drive/1JVEgkWpUJehgpsewTMSt1ErLHFK9I35J?usp=sharing)

### C) PyTorch Class-Based
* **Description:** Utilizing `nn.Module` and built-in optimizers for a structured approach.
* [View Colab](https://colab.research.google.com/drive/1m0VnJSzWnCRVwy9syZa6lF8nM5g8rbpI?usp=sharing)

### D) PyTorch Lightning
* **Description:** High-level abstraction focusing on research code, removing boilerplate.
* [View Colab](https://colab.research.google.com/drive/1yA3o2d6oNwH-SpGo7UKuvhGJUHaWx7ie?usp=sharing)

### E) TensorFlow Variants
* **i) Low Level:** Manual gradient tapes and variable management.[View Colab](https://colab.research.google.com/drive/1Z7udp5pXaPyWwtIR6uTpq4CB9zlc2V6Q?usp=sharing)
* **ii) Built-in Layers:** Using `tf.keras.layers`.[View Colab](https://colab.research.google.com/drive/1Nc63Ua4b8Os1HRM_uy5IF7HF0hyy9zEO?usp=sharing)
* **iii) Functional API:** Building complex topologies.[View Colab](https://colab.research.google.com/drive/1kglvC_RqFsRyg3zQjogxiqM9SyOSJkxX?usp=sharing)
* **iv) Model Subclassing:** Fully customizable object-oriented approach.[View Colab](https://colab.research.google.com/drive/1fhbKslcXXSPzLY6lJm24O8NZI3iJkAYV?usp=sharing)

---

## 📊 Data Visualization
The regression tasks target a non-linear equation with 3 variables:
$$y = f(x_1, x_2, x_3)$$
Dimensionality reduction (PCA/TSNE) was used to visualize the 4D relationship in a 3D space for clarity.

## 🛠 SOLID Principles
All notebooks are organized following SOLID principles to ensure code modularity, readability, and reproducibility.
