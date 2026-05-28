# 🖼️ Multi-Dataset Image Classification

A collection of deep learning models for image classification built using Convolutional Neural Networks (CNN), trained and evaluated across three diverse datasets — **MNIST**, **CIFAR-10**, and a fun **Chihuahua vs Muffin** Kaggle challenge.

> Built by [Tanya Yadav](https://github.com/Tanya-yadav-bit) | B.Tech CSE (AI & ML) — KIET Group of Institutions

---

## 📁 Repository Structure

```
Multi-Dataset-Image-Classification/
│
├── MNIST/
│   ├── mnist_classification.ipynb      # Handwritten digit recognition (0–9)
│   └── dataset/                 # Dataset 
│
├── CIFAR-10/
│   ├── cifar10_classification.ipynb    # 10-class object recognition
│
├── Chihuahua-vs-Muffin/
│   ├── chihuahua_muffin.ipynb          # Binary image classification
│
└── README.md
```

---

## 📊 Datasets Overview

| Dataset | Type | Classes | Images | Source |
|---|---|---|---|---|
| MNIST | Grayscale (28×28) | 10 (digits 0–9) | 70,000 | `tensorflow.keras.datasets` |
| CIFAR-10 | Color (32×32) | 10 (objects) | 60,000 | `tensorflow.keras.datasets` |
| Chihuahua vs Muffin | Color (varies) | 2 (binary) | Kaggle | [Kaggle Dataset](https://www.kaggle.com/datasets/samuelcortinhas/muffin-vs-chihuahua-image-classification/data) |

---

## 🧠 Models & Techniques Used

- **Architecture:** Convolutional Neural Network (CNN)
- **Frameworks:** TensorFlow, Keras
- **Preprocessing:** Normalization, Resizing, Grayscale conversion
- **Augmentation:** Horizontal flip, Rotation, Zoom (CIFAR-10 & Chihuahua)
- **Regularization:** Dropout layers to prevent overfitting
- **Optimization:** Adam optimizer with categorical/binary cross-entropy loss
- **Evaluation:** Accuracy, Loss curves, Confusion Matrix, Classification Report

---

## 🔍 Project Highlights

### 1️⃣ MNIST — Handwritten Digit Recognition
- Trained a CNN on 60,000 training images of handwritten digits (0–9)
- Applied normalization and reshaping for grayscale input
- Achieved high test accuracy with minimal overfitting
- Visualized predictions and misclassified samples

### 2️⃣ CIFAR-10 — Object Recognition
- Classified 10 categories: airplane, car, bird, cat, deer, dog, frog, horse, ship, truck
- Used data augmentation to improve model generalization on color images
- Compared performance with and without augmentation
- Plotted training vs validation accuracy/loss curves

### 3️⃣ Chihuahua vs Muffin — Kaggle Binary Classification
- A fun and challenging binary classification task (they genuinely look alike!)
- Built custom image data pipeline with augmentation
- Applied transfer learning concepts and fine-tuning for better accuracy
- Evaluated using binary accuracy and confusion matrix

---

## 🚀 How to Run

### Prerequisites
```bash
pip install tensorflow keras numpy matplotlib seaborn scikit-learn pandas
```

### Run any notebook
```bash
# Clone the repo
git clone https://github.com/Tanya-yadav-bit/Multi-Dataset-Image-Classification-.git
cd Multi-Dataset-Image-Classification-

# Open Jupyter
jupyter notebook

# Navigate to any folder and open the .ipynb file
```

Or open directly in **Google Colab** — click the badge below:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

---

## 📈 Results Summary

| Dataset | Test Accuracy |
|---|---|
| MNIST | ~97% |
| CIFAR-10 | ~75–80% |
| Chihuahua vs Muffin | ~85–90% |

> Note: Results may vary slightly based on random seed and number of epochs trained.

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-red?logo=keras)
![Kaggle](https://img.shields.io/badge/Kaggle-Dataset-blue?logo=kaggle)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)

---

## 👩‍💻 Author

**Tanya Yadav**
B.Tech CSE (AI & ML) | KIET Group of Institutions

[![GitHub](https://img.shields.io/badge/GitHub-Tanya--yadav--bit-black?logo=github)](https://github.com/Tanya-yadav-bit)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Tanya%20Yadav-blue?logo=linkedin)](https://www.linkedin.com/in/tanya-yadav-bb388b336/)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
