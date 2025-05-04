# 😊 Facial Emotion Recognition using CNN (FER-2013)

This project implements a Convolutional Neural Network (CNN) to classify facial expressions into emotions using the FER-2013 dataset. It enables machines to understand human emotions visually, with potential applications in human-computer interaction, mental health analysis, and intelligent surveillance.

---

## 🧠 Model Overview

- **Dataset**: FER-2013 (Kaggle)
- **Architecture**: Custom-built CNN with convolutional, pooling, dropout, and dense layers
- **Input**: Grayscale facial images (48x48 pixels)
- **Output Classes**:
  - 😠 Angry
  - 😒 Disgust
  - 😨 Fear
  - 😄 Happy
  - 😢 Sad
  - 😲 Surprise
  - 😐 Neutral

---

## 📂 Dataset

- **Source**: [FER-2013 on Kaggle](https://www.kaggle.com/datasets/msambare/fer2013)
- **Format**: CSV file with pixel data and labels
- **Size**: ~35,000 images labeled across 7 emotions

> ⚠️ Dataset is not included in this repository. Please download it from [Kaggle](https://www.kaggle.com/datasets/msambare/fer2013) and place the CSV file inside the `data/` directory.

---

## 🧪 Libraries Used
Python

TensorFlow / Keras

NumPy, Pandas

OpenCV (for image preprocessing and webcam support)

Matplotlib & Seaborn (for visualization)

scikit-learn (for evaluation)


