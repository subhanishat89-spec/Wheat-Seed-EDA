# Wheat Seeds Dataset – Exploratory Data Analysis and CNN Classification

## Project Overview
This repository contains two major components of a course project on wheat seed image classification.
Task 1 focuses on Exploratory Data Analysis (EDA) and related work, while Task 2 focuses on supervised learning using pre-trained Convolutional Neural Networks (CNNs).

## Task 1: Exploratory Data Analysis (EDA)
# Objective
The objective of Task 1 is to analyze and understand the wheat seed image dataset before applying deep learning models.

## Contents
- EDA notebook (Colab Notebook)
- Visualizations of class distribution
- Sample images from each wheat variety
- Image width and height distribution analysis

## Tools Used
- Python
- NumPy
- Matplotlib
- Seaborn
- PIL (Pillow)

## Project Report
The detailed related work analysis and EDA report for this project is available in the PDF file:
CSE-366 related work Group-3.pdf

## Course
CSE366 – Artificial Intelligence  
Assignment: Related Work & EDA

---

# Task 2: Supervised Pre-trained CNN Baselines

## Objective
This task implements and evaluates multiple pre-trained Convolutional Neural Network (CNN) architectures using transfer learning for wheat seed image classification. All models are trained under identical conditions to ensure fair comparison.

## Models Used
- EfficientNetB0
- ResNet50
- VGG16

## Training Setup
- Image size: 224 × 224
- Batch size: 32
- Epochs: 50
- Optimizer: Adam
- Loss function: Categorical Cross-Entropy
- Transfer learning with frozen base layers

## Evaluation Metrics
The following metrics are reported for each model:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC Curve & AUC
- Training Time

## Statistical Comparison
A paired t-test is used to statistically compare model performance:
- EfficientNet vs ResNet
- EfficientNet vs VGG
- ResNet vs VGG

p-value < 0.05 indicates a statistically significant difference.

## Repository Structure
- Task2_EfficientNet.ipynb
- Task2_ResNet.ipynb
- Task2_VGG.ipynb
- Task2_Comparison.ipynb
- Task2/Task2_Results/ (CSV and NPY evaluation files)

## Notes
- All experiments were run in Google Colab
- Dataset stored in Google Drive
- Results saved for reproducibility and fair comparison

## Course
CSE366 – Artificial Intelligence  
Assignment: Supervised Pre-trained CNN Models
