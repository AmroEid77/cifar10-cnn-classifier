# 📦 CIFAR-10 Image Classification with CNN

This project implements a Convolutional Neural Network (CNN) for image classification using the CIFAR-10 dataset. Built with TensorFlow and Keras, the model aims to accurately classify images into one of ten classes, such as airplane, dog, ship, etc.

---

## 🔍 Overview

- 🧠 Deep learning model using Convolutional Neural Networks (CNN)
- 🖼️ Trained on the CIFAR-10 dataset (60,000 32x32 RGB images)
- 🔬 Includes data preprocessing, training, evaluation, and visualization
- 📈 Achieves high accuracy on image classification tasks

---

## 🧾 Dataset

The **CIFAR-10** dataset consists of:

- 60,000 32×32 color images
- 10 classes with 6,000 images each
- 50,000 training images and 10,000 test images

### Classes:
`airplane`, `automobile`, `bird`, `cat`, `deer`, `dog`, `frog`, `horse`, `ship`, `truck`

---

## 🧠 Model Architecture

The model includes:

- 📥 Input layer with 32x32x3 image shape
- 🔄 Convolutional layers with ReLU activation
- 📉 MaxPooling layers for downsampling
- 🔁 Dropout layers to reduce overfitting
- 🔚 Fully-connected Dense layers
- 🧮 Output layer with Softmax activation (10 classes)

> Training and evaluation metrics such as accuracy and loss are plotted and visualized using Matplotlib.

---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/cifar10-cnn-classifier.git
cd cifar10-cnn-classifier
```

### 2. Install Dependencies
Make sure you have Python 3.7+ and pip installed. Then run:
```bash
pip install -r requirements.txt
```



