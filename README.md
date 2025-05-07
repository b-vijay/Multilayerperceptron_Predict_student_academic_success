# Student Dropout Prediction using Deep Learning

This project applies **deep learning** techniques to predict **student academic outcomes** (Graduate vs. Dropout) using a **Multi-Layer Perceptron (MLP)** model in **TensorFlow/Keras**. The goal is to support retention strategies by identifying students at risk early.

## Overview

As a data science and deep learning enthusiast, I worked on:

- **Data preprocessing**: Handled dataset with **categorical, binary, and numerical features**
- **Feature engineering**: Used embeddings for high-cardinality categories, normalized continuous features, and processed binary inputs efficiently
- **Model design**: Built a functional API-based MLP model with embedding layers, normalization, and dense layers with L2 regularization

## Model Highlights

- **Inputs**: 
  - Embedded categorical features
  - Normalized numerical features
  - Raw binary features
- **Architecture**: 2 hidden layers (32, 15 neurons), ReLU activation, sigmoid output
- **Training strategy**: Early stopping, learning rate scheduling, stratified 80/20 split

## Performance

| Metric           | Value     |
|------------------|-----------|
| Accuracy         | 91.05%    |
| ROC-AUC          | 0.8975    |
| Recall (Dropout) | 84%       |
| Recall (Graduate)| 96%       |

## Dataset & References

- **Dataset**: [UCI – Student Dropout & Success](https://doi.org/10.24432/C5MC89)
- **Paper**: Realinho et al. (2022), *Predicting Student Dropout and Academic Success*
