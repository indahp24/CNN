# 🫁 Pneumonia Detection using Deep Learning (CNN, ResNet50, MobileNetV2)

## Overview

This project focuses on detecting pneumonia from chest X-ray images using deep learning models. A comparative study is conducted to evaluate the performance of three different architectures: **Custom CNN**, **ResNet50**, and **MobileNetV2**.

---

## Objectives

* Build a deep learning model for pneumonia classification
* Compare performance across multiple architectures
* Identify the most efficient and accurate model

---

## Models Used

This project implements and compares the following models:

* **Custom CNN** → baseline model
* **ResNet50** → deep residual network
* **MobileNetV2** → lightweight and efficient model

---

## Dataset

The dataset consists of chest X-ray images categorized into:

* Normal
* Pneumonia

Data is split into:

* Training set
* Validation set
* Testing set

---

## Methodology

* Image resizing and normalization
* Data augmentation (training set only)
* Model training using TensorFlow/Keras
* Performance evaluation on test data

---

## Results & Comparison

| Model       | Accuracy | Notes                         |
| ----------- | -------- | ----------------------------- |
| CNN         | High     | Good baseline performance     |
| ResNet50    | Higher   | Strong feature extraction     |
| MobileNetV2 | Highest  | Best balance accuracy & speed |

> MobileNetV2 shows the best performance in terms of efficiency and accuracy.

---

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 🚀 How to Run

1. Open the notebook using Jupyter Notebook or Google Colab
2. Run each notebook to train and evaluate models

---

## Key Insight

* Deep architectures like ResNet50 improve feature learning
* MobileNetV2 provides excellent performance with lower computational cost
* Model comparison helps in selecting the best architecture for real-world deployment

---

## 👤 Author

Indah Putianik

---

## ⭐ Notes

This project demonstrates a comparative analysis approach in **Computer Vision**, highlighting model performance differences in medical image classification.

