# Arabic Sign Language Detection

<p align="center">
  <img src="https://github.com/AnfalAlkuraydis/Arabic-sign-language-detection/blob/main/assets/signLanguage.png" width="650"/>
</p>

---

## 📝 Abstract
Arabic Sign Language (ArSL) is the main communication medium for the deaf community in the Arab world.  
This project presents a **deep learning–based recognition system** for the Arabic manual alphabet, enabling real-time sign detection through image inputs.  
Our trained model achieves **90% accuracy** on the benchmark dataset, offering a step forward in accessible technology for communication.

---

## 📖 Overview
- Preprocess RGB hand sign images (resize, normalize).
- Train a deep CNN / transfer learning model (MobileNetV2).
- Validate on held-out test data.
- Deploy a **live demo app** that predicts hand signs from the camera.

---

## 🔄 Pipeline
1. **Dataset**: [RGB Arabic Alphabets Sign Language Dataset](https://www.kaggle.com/datasets/muhammadalbrham/rgb-arabic-alphabets-sign-language-dataset)  
2. **Preprocessing**: image resizing, normalization, one-hot encoding.  
3. **Modeling**: deep CNN with augmentation + callbacks (early stopping, learning rate scheduling).  
4. **Training**: stratified train/val/test split.  
5. **Evaluation**: accuracy, confusion matrix, per-class performance.  
6. **Deployment**: web-based demo for real-time recognition.

---

## 📊 Dataset
- **Source**: [Kaggle dataset](https://www.kaggle.com/datasets/muhammadalbrham/rgb-arabic-alphabets-sign-language-dataset)  
- 32 Arabic alphabet classes.  
- Color images (RGB).  

---

## 🎯 Results
Model achieves around **90% accuracy** on the test set.  

---

## 🖥️ Demo
The system can run in real time with webcam input:  

<p align="center">
  <img src="https://github.com/AnfalAlkuraydis/Arabic-sign-language-detection/blob/main/assets/results.jpg" width="500"/>
</p>

---

## ⚙️ Installation

Clone the repository:
```bash
git clone https://github.com/AnfalAlkuraydis/Arabic-sign-language-detection.git
cd Arabic-sign-language-detection
