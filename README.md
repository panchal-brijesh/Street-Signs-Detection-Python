## 🚦 Detection of Street Signs

### Project Title
Detection of Street Signs

### Author
Brijeshkumar Vijaykumar Panchal

### Matriculation Number
221607

### Course
Master of Mechatronics and Robotics

### Semester
Wintersemester 2024/25

### Subject
Computer & Robot Vision

### Supervisor
Prof. Dr. rer. nat. Dieter Maier

---

## Introduction

This project involves developing a street sign detection system using both **YOLO Neural Networks** and **Classical Image Processing** techniques. The goal is to enable real-time, robust detection of street signs to support applications such as **autonomous vehicles**, **traffic monitoring systems**, and **smart city infrastructure**.

---

## Classical_Image_Processing_Template Matching.ipynb

The file is too large for GitHub. You can view or download it here:  
👉 [View on Google Drive](https://colab.research.google.com/drive/1RdYeh7diCsxSvcStmR_fM_NRzaF7e_Rp?usp=drive_link)

---

## Project Overview

- **YOLOv8 (You Only Look Once):** For fast, real-time object detection.
- **Classical Image Processing:** For sign detection using OpenCV-based methods.
- **Application:** Enhances traffic safety by detecting and classifying street signs from visual input.

---

## Tools

- **YOLOv8** – Real-time object detection
- **OpenCV** – Classical image processing
- **Google Colab** – Training & inference
- **Python** – Core programming language
- **Roboflow** – Dataset preparation

---

## Dataset

- **Source:** Collected using [Roboflow](https://roboflow.com/)
- **Annotations:** Labeled in YOLO format.
- **Classes:** Includes various types of street signs (e.g., Stop, Speed Limit, Yield).
- **Data Augmentation:** Rotation, scaling, flipping, and brightness adjustments were applied to improve robustness.

---

## Tasks Performed

- **Preprocessing:** Enhanced image quality for better detection.
- **Feature Extraction:** Detected and classified various street signs.
- **Real-time Inference:** Performed live detection using trained YOLOv8 model.

---

## Training Configuration

- **Optimizer:** SGD
- **Batch size:** 32
- **Learning rate:** 0.001
- **Epochs:** 20
- **Model:** YOLOv8

---

## Evaluation

- **Confusion Matrix:** Analyzed model accuracy and misclassifications.
- **Precision-Recall Curve:** Evaluated model performance across thresholds.

---

## Challenges & Solutions

- **Lighting and Angles:** Solved with data augmentation (brightness/rotation).
- **Occlusions:** Model trained on partially visible signs for robustness.

---

## YOLO vs. Classical Image Processing

| Criteria               | YOLOv8 (DL) | Classical (CV) |
|------------------------|-------------|----------------|
| Accuracy               | High        | Moderate       |
| Real-time Performance  | Yes         | Limited        |
| Robustness             | High        | Low            |
| Dataset Dependency     | High        | Low            |
| Implementation Time    | Moderate    | Low            |
