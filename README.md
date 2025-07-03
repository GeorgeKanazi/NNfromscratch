# Deep Learning from Scratch: MNIST Classification

This project implements a multi-layer neural network using **low-level PyTorch tensor operations** to build the training process from the ground up. The goal was to gain a deep understanding of how forward and backward propagation work under the hood, including techniques like **batch normalization** and **L2 regularization**.

> 🧠 Completed as part of the Deep Learning course in the B.Sc. Data Science program at Ben-Gurion University.

## 📌 Project Highlights
- Full manual implementation of forward & backward propagation
- Batch normalization
- L2 regularization
- Training on the MNIST dataset with different batch sizes
- Accuracy and performance comparison across variations

## 🧠 Network Architecture
- Layers: `[784, 20, 7, 5, 10]`
- Activation: ReLU (hidden), Softmax (output)
- Loss: Categorical Cross-Entropy
- Optimizer: Gradient Descent (manual implementation)

## 📊 Key Results

| Configuration              | Best Batch Size | Test Accuracy | Runtime (s) |
|---------------------------|-----------------|---------------|-------------|
| Without BatchNorm / L2    | 16              | 0.9212        | 37.5        |
| With BatchNorm            | 128             | 0.913         | 69.2        |
| With L2 Regularization    | 16              | ~0.94         | 113         |
| BatchNorm + L2            | 64              | 0.915         | 112         |

## 📁 Files
- `Deep_Learning_from_scratch.ipynb` – Implementation and training code
- `mnist_classification_report.pdf` – Summary of results and analysis
- `Assignment_instructions.docx` – Original assignment brief

## 🛠 Technologies
- Python 3
- PyTorch (tensor ops only)
- NumPy
- Matplotlib

## 👨‍💻 Authors
- George Kanazi – [GitHub](https://github.com/GeorgeKanazi)
- Ammar Mnaa - [GitHub](https://github.com/AmarMnaa)
