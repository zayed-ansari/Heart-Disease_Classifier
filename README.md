# Heart-Disease_Classifier
This repository contains a machine learning project for predicting heart disease using the UCI Heart Disease dataset. It evaluates multiple classification algorithms, including Logistic Regression, K-Nearest Neighbors, and Random Forest, with metrics like accuracy, precision, and recall to determine model performance and effectiveness.


# Heart Disease Prediction

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Model Evaluation](#model-evaluation)
- [Conclusion](#conclusion)
- [Requirements](#requirements)
- [Usage](#usage)
- [License](#license)

## Introduction
The Heart Disease Prediction project aims to develop machine learning models to predict the presence of heart disease in patients based on various health parameters. This project utilizes the UCI Heart Disease dataset to train and evaluate multiple classification algorithms.

## Dataset
The dataset used in this project is the Heart Disease dataset, which contains several health metrics and a binary target indicating the presence or absence of heart disease.
https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

## Methodology
1. **Data Preprocessing**:
   - Load the dataset and preprocess it for analysis.

2. **Model Training**:
   - Train multiple models: Logistic Regression, K-Nearest Neighbors (KNN), and Random Forest.

3. **Model Evaluation**:
   - Evaluate model performance using accuracy and other relevant metrics.

## Model Evaluation Results
### Logistic Regression
- Accuracy: 86%
- Precision: 0 -> 0.92, 1 -> 0.82
- Recall: 0 -> 0.81, 1 -> 0.93

### K-Nearest Neighbors (KNN)
- Accuracy: 100%
- Precision: 0 -> 1.00, 1 -> 1.00
- Recall: 0 -> 1.00, 1 -> 1.00

### Random Forest
- Accuracy: 100%
- Precision: 0 -> 1.00, 1 -> 1.00
- Recall: 0 -> 1.00, 1 -> 1.00

## Conclusion
This project demonstrates the application of machine learning techniques to predict heart disease. The models showed promising accuracy, with KNN and Random Forest achieving 100% accuracy.

## Requirements
- Python 3.13.0
- pandas
- numpy
- scikit-learn

You can install the required packages using pip:
```bash
pip install pandas numpy scikit-learn
