# 🩺 Pneumonia Diagnosis from Chest X-rays using CNN

This project uses **Convolutional Neural Networks (CNNs)** to classify chest X-ray images as either **Pneumonia** or **Normal**. It was developed as part of my internship to explore deep learning in medical image analysis.

By training the model on labeled chest X-ray data, it can automatically learn the visual patterns associated with pneumonia, helping in faster and automated preliminary diagnosis.

---

## 📌 Highlights

- 📂 Dataset: Chest X-ray images (2 classes: Pneumonia, Normal)
- 🧠 Model: CNN built using TensorFlow and Keras
- 🖼️ Input: Grayscale images resized to (150x150)
- ⚙️ Training & Validation: Using Keras ImageDataGenerator
- 📈 Output: Accuracy and loss graphs

---

## 🚀 How to Run the Project

### 1. Clone the repository:
```bash
git clone https://github.com/TejaswinisGit/Diagnosis.git
cd Diagnosis
```

### 2. Install required libraries:
```bash
pip install tensorflow matplotlib numpy
```

### 3. Prepare dataset:
- Place your X-ray images in a `chest_xray` folder with this structure:
  ```
  chest_xray/
  ├── train/
  │   ├── NORMAL/
  │   └── PNEUMONIA/
  ├── val/
  │   ├── NORMAL/
  │   └── PNEUMONIA/
  └── test/
      ├── NORMAL/
      └── PNEUMONIA/
  ```

### 4. Run the script:
```bash
python Diagnosis.py
```

---

## 📚 What I Learned

Through this project, I gained practical experience in:

- Preprocessing real-world medical image data
- Using CNNs to detect visual patterns
- Understanding data augmentation and model overfitting
- Applying deep learning for binary classification problems

This project helped me understand how deep learning models can be applied to the healthcare domain for faster diagnostics.

---

## 👩‍💻 About Me

I'm **Tejaswini Thungathoorthi**, a Computer Science and Engineering student specializing in **AI and Machine Learning**. I'm passionate about using technology to solve real-world problems, and this project is a step toward impactful healthcare solutions using AI.

---

## 📬 Contact

- 📧 Email: [tejaswini17109@gmail.com]  
- 💼 LinkedIn: [https://www.linkedin.com/in/tejaswini-thungathoorthi-9076b2295/]
