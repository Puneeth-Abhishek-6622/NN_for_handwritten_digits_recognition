# 🧠 Digit Recognition using Neural Networks (Keras)

This repository contains a neural network model built with Keras for digit recognition. Each digit is represented as a **7x7 grid**, where every pixel has an intensity value ranging from **1 to 255**. The **7x7 matrix** is flattened into a **1D vector (49 values per sample)** before being processed by the neural network.  

## 🚀 Features  
- **Input:** Flattened 1D vector (49 values per sample)  
- **Model:** Fully Connected Neural Network (MLP) using Keras  
- **Activation Functions:**  
  - 🔹 **ReLU** for hidden layers  
  - 🔹 **Sigmoid** for the output layer  
- **Loss Function:** Binary Crossentropy (for binary classification) / Categorical Crossentropy (for multi-class)  
- **Optimizer:** Adam  


