# EnsembleAi
# NdLinear vs Linear Benchmark on Fashion-MNIST 👟📊

This project compares a standard neural network using `nn.Linear` layers with a compressed model using Ensemble’s `NdLinear` layer on the Fashion-MNIST dataset.

## 📌 Objective
Evaluate the performance difference between a traditional fully connected architecture and one utilizing NdLinear, a novel layer designed to reduce parameter size while maintaining accuracy.

## 🧠 Dataset
I used the [Fashion-MNIST dataset](https://github.com/zalandoresearch/fashion-mnist), which consists of 28x28 grayscale images of fashion items across 10 classes.

## 🛠️ Tools & Libraries
- Python
- PyTorch
- TorchVision
- Matplotlib
- [NdLinear GitHub Repo](https://github.com/ensemble-core/NdLinear)

## 📈 Results

| Model          | Accuracy | Final Training Loss |
|----------------|----------|---------------------|
| Standard Model | 86.05%   | 0.3582              |
| NdLinear Model | 83.31%   | 0.4645              |

NdLinear achieved comparable accuracy with a reduced parameter count, demonstrating its potential for lightweight and efficient deployment.

## 📚 What I Learned
This project helped me understand how compressed layers like `NdLinear` can significantly reduce model size with minimal trade-off in performance, which is especially valuable for ML deployment in resource-constrained environments.


