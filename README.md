# 🌾 HuskNet: Deep Learning Based Multi-class Classification of Husk Species in Bangladesh

This repository contains the official code and resources for the research paper,  
**["HuskNet: A Deep Learning Model for Classifying Husk Species."](https://www.researchgate.net/publication/381640044_HuskNet_Deep_Learning_Based_Multi-class_Classification_of_Husk_Species_in_Bangladesh)**

---

## 📖 Project Overview

In an agriculture-dependent country like Bangladesh, cattle play a vital role in farming and meeting nutritional demands.  
Husks, the protective coverings of plants, are a key and easily available component of cattle feed.  
Understanding the nutritional content of different husk species is crucial for formulating balanced and cost-effective diets for livestock.

This project introduces **HuskNet**, a deep learning model designed to accurately classify eight common husk species found in Bangladesh.  
By leveraging computer vision, HuskNet aims to provide a data-driven approach to enhance cattle feed formulation, ultimately supporting more sustainable agricultural practices and improving livestock productivity.

---

## 🌾 The BDHusk Dataset

The model was trained and evaluated on the **[BDHusk dataset](https://data.mendeley.com/datasets/h754ntdtfx/1)**, which includes:

- **Content**: A comprehensive collection of images from eight different husk species commonly found in Bangladesh.
- **Classes (8 total)**:  
  - Rice Husk  
  - Corn Husk  
  - Wheat Husk  
  - Chickpea Husk  
  - Lentil Husk  
  - Soybean Husk  
  - Grass Pea Husk  
  - Field Pea Husk
- **Size**: 2400 total images (300 per class).
- **Origin**: Images were captured in the **Sirajganj district of Bangladesh** using mobile camera devices.

---

## 🧠 Model Architecture: HuskNet

**HuskNet** is a deep learning model specifically tailored for this multi-class classification task.

- **Base Architecture**: Built on the powerful **ResNet50** architecture, utilizing transfer learning.
- **Modifications**:  
  - Output layer with **8 neurons** (one for each husk class).  
  - **Softmax activation function** for multi-class predictions.

---

## 📊 Performance & Results

HuskNet demonstrated exceptional performance across all evaluation metrics:

- **Average Accuracy**:  
  - Achieved **97% average accuracy** across all eight classes.
- **ROC Curve Analysis**:  
  - Achieved **perfect micro-average AUC score of 100%**.
- **Class-Specific Metrics**:  
  - High precision, recall, and F1-scores for each class.  
  - F1-scores reached up to **99% for Corn, Lentil, and Field Pea husks**.

---

## 💻 Tech Stack & Environment

- **Software & Libraries**:  
  - Python  
  - TensorFlow  
  - Keras  
  - Scikit-learn  
  - NumPy  
  - Seaborn

- **Hardware**:  
  - Intel Core i7 CPU  
  - 32GB RAM  
  - Nvidia RTX 3060Ti GPU
