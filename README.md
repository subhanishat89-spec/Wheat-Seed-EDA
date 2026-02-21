Wheat Seeds Dataset – Exploratory Data Analysis and CNN Classification
Project Overview
This repository contains two main parts of a course project for wheat seed image classification.
Task 1 focuses on Exploratory Data Analysis (EDA) and related work, while Task 2 focuses on supervised deep learning using pre-trained Convolutional Neural Networks (CNNs).

Task 1: Exploratory Data Analysis (EDA)
Objective
The goal of Task 1 is to understand the wheat seed image dataset through exploratory analysis before applying deep learning models.

Contents
EDA notebook (Google Colab notebook)

Visualizations of class distribution

Sample images from each wheat variety

Image width and height distribution analysis

Tools Used
Python

NumPy

Matplotlib

Seaborn

PIL (Pillow)

Project Report
The detailed related work analysis and EDA report for this task is provided in the PDF file:
CSE-366 related work Group-3.pdf

Task 2: Supervised Pre-trained CNN Baselines
Objective
Task 2 implements and evaluates multiple pre-trained CNN architectures using transfer learning for wheat seed image classification.
All models are trained under identical conditions to ensure a fair comparison.

Models Used
EfficientNetB0

ResNet50

VGG16

Training Setup
Image size: 224 × 224

Batch size: 32

Epochs: 50

Optimizer: Adam

Loss function: Categorical Cross-Entropy

Transfer learning with frozen base layers

Evaluation Metrics
The following metrics are reported for each model:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

ROC Curve and AUC

Training time

Statistical Comparison
A paired t-test is used for statistical comparison of model performance:

EfficientNet vs ResNet

EfficientNet vs VGG

ResNet vs VGG

A p-value < 0.05 indicates a statistically significant difference between models.

Repository Structure
Task1_EDA.ipynb

Task2_EfficientNet.ipynb

Task2_ResNet.ipynb

Task2_VGG.ipynb

Task2_Comparison.ipynb

Task2/Task2_Results/ (CSV and NPY evaluation result files)

Notes
All experiments were conducted using Google Colab

The dataset is stored in Google Drive

Evaluation results are saved to ensure reproducibility and fair comparison

Course Information
Course: CSE366 – Artificial Intelligence
Assignment: Related Work, EDA, and Supervised Deep Learning Models
