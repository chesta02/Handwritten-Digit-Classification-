# ✍️ Handwritten Digit Classification

A deep learning project that classifies handwritten digits (0–9) using a Convolutional Neural Network (CNN) trained on the MNIST dataset. The model learns image features automatically and predicts the correct digit with high accuracy.

---

## 📌 Project Overview

Handwritten digit recognition is one of the most fundamental computer vision tasks. This project uses a CNN built with PyTorch to classify grayscale images of handwritten digits from the MNIST dataset.

---

## 🚀 Features

- Image preprocessing and normalization
- CNN-based image classification
- Training and validation on the MNIST dataset
- Performance evaluation using multiple metrics
- Prediction of handwritten digits

---

## 🛠️ Tech Stack

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📂 Project Structure

```
Handwritten-Digit-Classification/
│
├── Handwritten_digit_classification.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 📊 Dataset

**Dataset:** MNIST

- 70,000 grayscale handwritten digit images
- Image size: **28 × 28**
- Training samples: **60,000**
- Test samples: **10,000**
- Classes: **0–9**

---

## 🧠 Model Architecture

The CNN consists of:

- Convolutional Layers
- ReLU Activation
- Max Pooling Layers
- Fully Connected Layers
- Softmax Output for 10 Classes

---

## 📈 Evaluation Metrics

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/chesta02/Handwritten-Digit-Classification.git
```

Move into the project directory

```bash
cd Handwritten-Digit-Classification
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
Handwritten_digit_classification.ipynb
```

---

## 📌 Workflow

1. Load the MNIST dataset
2. Preprocess and normalize images
3. Create DataLoaders
4. Build the CNN model
5. Train the network
6. Evaluate performance
7. Predict handwritten digits

---

## 📌 Future Improvements

- Hyperparameter tuning
- Data augmentation
- Deploy using Streamlit or FastAPI
- Train on custom handwritten digit datasets

---

