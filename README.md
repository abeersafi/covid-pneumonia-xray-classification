# Deep Learning for Pneumonia and COVID-19 Classification from Chest Radiographs

## Overview

This project uses Deep Learning and Transfer Learning techniques to classify chest X-ray images into three categories:

* COVID-19
* Non-COVID Pneumonia
* Normal

The goal is to support healthcare professionals by providing an AI-based clinical decision support system for respiratory disease detection.

---

## Dataset

COVID-QU-Ex Dataset (2021)

* 33,920 Chest X-ray Images
* Balanced Class Distribution
* COVID-19
* Non-COVID Pneumonia
* Normal

---

## Methodology

### Preprocessing

* Lung Region Segmentation
* ROI Extraction
* Image Resizing
* Pixel Normalization

### Deep Learning Model

* ResNet-50 Transfer Learning
* Fine-Tuning of Higher Layers
* Data Augmentation
* SGD Optimization

### Explainability

* Grad-CAM Heatmaps
* Visual Verification of Model Attention

---

## Results

* Test Accuracy: 82%
* Weighted ROC-AUC: 0.9448
* COVID-19 F1-Score: 0.84

The model demonstrated strong discrimination capability between COVID-19, Pneumonia, and Normal chest radiographs.

---

## Clinical Relevance

This project explores how Artificial Intelligence can assist radiologists by reducing workload and improving diagnostic efficiency while remaining a decision-support tool rather than a replacement for clinicians.

---

## Authors

* Abeer Safi
* Jelan Hatoum
* Sude Sena Sarıkaya

Biomedical Engineering Department

Yıldız Technical University
