# Bone-Fracture-Classification-EfficientNetV2
Deep learning project for classifying bone fractures (Simple vs Comminuted) using EfficientNetV2 and transfer learning.

## 📌 Project Overview

This project implements EfficientNetV2 with transfer learning to classify bone fractures from X-ray images as part of a Capstone Project.

## 📄 Research Paper

Bone Fracture Classification Using Deep Learning Models with Transfer Learning
IEEE ISAS 2025

## 📊 Dataset

Talha et al. (2024) - X-ray Bone Fracture Dataset
https://www.kaggle.com/datasets/orvile/simple-vs-comminuted-fractures-x-ray-data

* Total Images Used: **2384 (Original Only)**
* Classes:

  * Simple Bone Fracture
  * Comminuted Bone Fracture

> Dataset not included due to size limitations.

## 🧠 Model

* EfficientNetV2 (Transfer Learning)
* Binary Classification

## ⚙️ Tools & Technologies

* Python
* TensorFlow / Keras
* Google Colab
* Scikit-learn
* Matplotlib / Seaborn

## 📈 Results

* Accuracy: ~57%
* ROC Curve
* Confusion Matrix
* AUC Score: ~0.62

## 📊 Interpretation

The model shows better performance in detecting simple fractures, but lower accuracy in identifying comminuted fractures.

## 🎯 Objective

To reproduce the methodology of the research paper using EfficientNetV2.

## 🚀 Future Improvements

* Fine-tuning model
* Hyperparameter tuning
* Cross-validation
