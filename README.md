# 🏃‍♂️ Human Gait Classification (Good Gait / Bad Gait)

This project classifies human gait as either **Good Gait** or **Bad Gait** using a Convolutional Neural Network (CNN), trained entirely in **Google Colab** using TensorFlow and Keras.

---

## 📌 Overview

- **Goal:** Identify improper or abnormal walking posture (Bad Gait) versus normal walking (Good Gait).
- **Dataset:** CASIA Gait Dataset B (manually labeled subset).
- **Platform:** Google Colab (GPU-accelerated).
- **Frameworks & Tools:** 
  - TensorFlow / Keras  
  - scikit-learn  
  - matplotlib, seaborn (for plots)  
  - Google Drive (for dataset/model storage)

---

## ▶️ Run on Colab

> All training, evaluation, and prediction code is implemented in the Colab notebook.

---

## 📁 Dataset

- Source: [CASIA Gait Dataset B](http://www.cbsr.ia.ac.cn/english/Gait%20Databases.asp)
- Preprocessing:
  - Silhouette images extracted and manually labeled as `good_gait` and `bad_gait`.
  - Images uploaded to Google Drive and accessed directly from Colab.

---


---

## 📊 Evaluation

Model was trained and validated in Colab using an 80/20 train-test split.

Metrics reported:
- Accuracy
- Precision
- Recall
- F1 Score

---

## 🔒 Notes

- This is a prototype built for experimentation and learning.
- For better generalization, future improvements may include:
  - Augmentation for different camera angles & lighting
  - Real-time pose estimation (e.g., MediaPipe) for feedback
  
---

## ©️ Credits

- CASIA Gait Dataset B – Chinese Academy of Sciences
- Built using TensorFlow, Keras, and scikit-learn on Google Colab.



