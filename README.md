# Heart Disease Risk Prediction

## Digital Transformation in Enterprise Systems (TDSE) - Lab 2

## Nicolás Toro Criollo

---

## Intro

This project implements a Logistic Regression model from scratch using only NumPy, Pandas, and Matplotlib to predict the presence of heart disease.

The project includes:

- Exploratory Data Analysis (EDA)
- Data preprocessing
- Stratified train/test split
- Feature normalization
- Logistic Regression implementation from scratch
- Model evaluation using Accuracy, Precision, Recall, and F1-Score
- Decision boundary visualization
- L2 Regularization
- Training and testing in Amazon SageMaker

The objective is to understand the complete implementation of Logistic Regression without relying on machine learning libraries.

---


## Project Structure

```
.
├── heart_disease_lr_analysis.ipynb
├── heart.csv
├── README.md
└── images/
    ├── sagemaker_notebook.png
    ├── training_completed.png
    └── test_metrics.png
```

---

## How to Run

1. Clone or download the repository.
2. Place `heart.csv` in the project directory.
3. Open `heart_disease_lr_analysis.ipynb`.
4. Execute all notebook cells in order.
5. Review the generated figures, tables, and evaluation metrics.

---

## Dataset Description

The project uses the Heart Disease Dataset, which contains clinical information from patients and a binary target indicating the presence or absence of heart disease.

Selected features:

- Age
- Resting Blood Pressure (`trestbps`)
- Cholesterol (`chol`)
- Maximum Heart Rate (`thalach`)
- ST Depression (`oldpeak`)
- Number of Major Vessels (`ca`)

Target:

- 0 → No heart disease
- 1 → Heart disease

Dataset source:

https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

---

## Results

Best evaluation metrics obtained:

| Metric | Value |
|---------|------:|
| Accuracy | 0.7597 |
| Precision | 0.7414 |
| Recall | 0.8165 |
| F1-Score | 0.7771 |

The L2 regularization reduced the magnitude of the model weights while maintaining the same predictive performance, indicating that the original model already generalized well for the selected features.

---

## Repository

This repository contains all source code, dataset, notebook, figures, and documentation required for the assignment.
