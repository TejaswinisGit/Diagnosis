# 🧠 Real-time Identification of Pneumonia from X-ray Images using Deep Learning

This project focuses on detecting **Pneumonia** from **chest X-ray images** using **Convolutional Neural Networks (CNNs)**. The goal is to build a deep learning model capable of assisting radiologists and healthcare professionals in the early detection of pneumonia with high accuracy.

---

## 🎯 Aim

> **Develop an AI model for medical image analysis to assist in the diagnosis of diseases.**

---

## 📝 Project Description

This project leverages **deep learning techniques** for **medical image classification**, enabling automated disease detection through chest X-ray image analysis. The solution applies a CNN-based approach to classify X-ray images into "Normal" or "Pneumonia", contributing to fast and reliable diagnostic support in healthcare.

---

## 🧠 What You Learn

- Medical Image Analysis
- Deep Learning in Healthcare
- TensorFlow-based CNN Implementation
- Handling Real-world Medical Datasets

---

## 🩺 Domain: Medical Image Analysis

This project belongs to the **Medical Image Analysis** domain. It applies artificial intelligence to healthcare by using image data to assist medical professionals in identifying pneumonia from chest X-rays.

---

## 💻 Technologies Used

- `Python`
- `TensorFlow` / `Keras`
- `Matplotlib`, `NumPy`
- Chest X-ray Dataset (Kaggle)
- Git LFS for dataset tracking

> ✅ You can extend or adapt this project using PyTorch, OpenCV, or FastAI.

---

## 🔍 Dataset Details

- **Source**: [Kaggle - Chest X-ray Pneumonia Dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
- Contains categorized images:
  - `NORMAL`
  - `PNEUMONIA`
- Organized into:
  - `train/`
  - `test/`
  - `val/`

Ensure the dataset is downloaded and placed in the `chest_xray/` directory.

---

## 🧪 Model Architecture

Built using **TensorFlow** and **Keras**:
- **Conv2D Layers** (32, 64, 128 filters) with ReLU activation
- **MaxPooling2D** after each convolution layer
- **Flatten Layer**
- **Dense Layer** (128 units)
- **Output Layer** with Sigmoid activation (binary classification)

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/TejaswinisGit/Diagnosis.git
cd Diagnosis
```

### 2️⃣ Install Required Packages
```bash
pip install tensorflow numpy matplotlib
```

### 3️⃣ Prepare the Dataset
Download the dataset from Kaggle:  
[🔗 Chest X-ray Pneumonia Dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)

Extract it into the project folder like this:
```
Diagnosis/
├── Diagnosis.py
├── chest_xray/
│   ├── train/
│   ├── test/
│   └── val/
```

### 4️⃣ Run the Python Script
```bash
python Diagnosis.py
```

