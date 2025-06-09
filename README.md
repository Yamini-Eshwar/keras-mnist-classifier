# Keras MNIST Classifier 🧠🔢

This repository contains a neural network built using TensorFlow and Keras to classify handwritten digits (0–9) from the MNIST dataset.

## 📌 Project Highlights

- Built with `keras.Sequential`
- Achieved **97.6% test accuracy**
- Visualized results using a **confusion matrix** and **heatmap**
- Compared models with **sigmoid** and **ReLU** activation functions

## 📊 Model Comparison

| Model Architecture            | Activation Function | Accuracy |
|------------------------------|---------------------|----------|
| 1 Dense Layer (10 units)     | Sigmoid             | ~92.6%   |
| 1 Hidden Layer (100 units) + Dense(10) | ReLU → Sigmoid     | ~97.6%   |

## 🔧 Libraries Used

- TensorFlow / Keras
- NumPy
- Matplotlib
- Seaborn

## 🧪 How to Run

```bash
# Install dependencies
pip install tensorflow matplotlib seaborn

# Run the notebook or Python file
python mnist_classifier.py
