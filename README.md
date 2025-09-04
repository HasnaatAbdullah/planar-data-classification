# planar-data-classification
Implementation of a 2-class classification neural network with a single hidden layer from scratch using NumPy. Includes forward propagation, backward propagation, cost computation, and parameter updates to classify planar datasets.
# 🌿 Planar Data Classification with One Hidden Layer 🧠

This repository contains my implementation of a **2-class classification neural network** from scratch using **NumPy**.  
The model is trained to classify a **planar dataset** using a **single hidden layer** with **tanh** activation and a **sigmoid** output layer.

---

## 🚀 Project Overview
This project demonstrates how to implement a **basic neural network** from scratch without using high-level deep learning libraries like TensorFlow or Keras.  
The goal is to classify points in a **2D dataset** into two categories based on learned decision boundaries.

**Key Learning Outcomes**:
- Build a **binary classification neural network** with **one hidden layer**.
- Use **non-linear activation functions** like **tanh**.
- Implement **forward propagation** and **backward propagation** manually.
- Compute the **cross-entropy loss**.
- Update model parameters using **gradient descent**.
- Visualize decision boundaries and experiment with **hidden layer sizes**.

---

## 📌 Key Features
- 🔹 Implements a **simple neural network** from scratch using NumPy.
- 🔹 Supports binary classification of **planar datasets**.
- 🔹 Uses **tanh** activation in the hidden layer and **sigmoid** in the output layer.
- 🔹 Implements forward & backward propagation **manually**.
- 🔹 Includes a cost function for model optimization.
- 🔹 Visualizes classification decision boundaries.

---

## 🧩 Model Architecture

| Layer | Type              | Activation |
|-------|--------------------|------------|
| Input | 2D Planar Features | -          |
| Hidden | Fully Connected   | **tanh**   |
| Output| Fully Connected    | **sigmoid**|

**Loss Function**: Binary Cross-Entropy  
**Optimizer**: Gradient Descent  

<p align="center">
  <img src="https://i.imgur.com/RLX3cS7.png" alt="Planar Data Classification" width="650"/>
</p>

---

## 📂 Project Structure

```bash
planar-data-classification/
│── data/                    # Dataset files (2D planar points)
│── notebooks/               # Jupyter notebook implementation
│── images/                  # Visualizations & decision boundaries
│── utils/                   # Helper functions for forward & backward propagation
│── models/                  # Saved trained models
│── results/                 # Accuracy curves & evaluation metrics
│── requirements.txt         # Project dependencies
└── README.md                # Documentation
