# 🧠 Artificial Neural Network (ANN) From Scratch Using Python + NumPy

This repository implements a **regression-only fully connected Artificial Neural Network (ANN)** built from **scratch** using **Python** and **NumPy**.  
It is specifically designed for **regression problems**, featuring a **linear activation in the final layer** and using **Mean Squared Error (MSE)** as the cost function., without relying on machine-learning frameworks like TensorFlow or PyTorch.

The project demonstrates how neural networks work internally by manually implementing:

- Layers  
- Sigmoid activation  
- Forward propagation  
- Backpropagation  
- Gradient descent  
- Cost function (Mean Squared Error)  
- Training loop  

---

## 🚀 Features

- **Custom NNLayer class** with:
  - Weight & bias initialization  
  - Sigmoid activation and derivative  
  - Forward propagation  
  - Backpropagation and gradient updates  

- **Flexible ANN class** that:
  - Allows adding layers dynamically  
  - Performs forward & backward passes  
  - Computes gradients manually  
  - Trains the network using gradient descent  
  - Generates predictions  

- **Regression-ready model** using **Mean Squared Error (MSE)** as cost.

---

## 🧩 How the ANN Works

### **1. NNLayer**
Each layer performs:
```python
z = x @ W.T + b
activation(z)
```

Stores intermediate values for backpropagation.

### **2. ANN Class**
Handles the entire model:

- Connects and manages layers  
- Applies forward propagation  
- Computes gradients through backpropagation  
- Updates weights using gradient descent  

### **3. Cost Function**
Uses **MSE**:
```
cost = mean((y - output)^2)
```

---

## 🛠 Technologies Used

- **Python**
- **NumPy**

---

## 🎯 Learning Objectives

This ANN implementation is ideal for learning:

- How forward propagation works mathematically  
- How backpropagation derives and updates gradients  
- How neural networks optimize using gradient descent   
- How to build a fully functional ANN manually  
- How regression problems can be solved using neural networks  
- How parameters (weights & biases) evolve during training  

---

## ✅ Conclusion

This project demonstrates how a regression-based Artificial Neural Network (ANN) can be built completely from scratch using only Python and NumPy. By implementing every component manually—forward propagation, backpropagation, gradients, activation functions, and optimization—you gain a deep understanding of how neural networks truly work under the hood.  

While modern deep-learning frameworks automate these processes, building your own ANN provides valuable insight into the core mathematics and logic that power machine learning models today. This implementation serves as a strong foundation for expanding into more advanced architectures such as classification networks, multi-layer perceptrons, and even deep learning frameworks.


