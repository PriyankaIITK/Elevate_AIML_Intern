# Binary Classification using Logistic Regression (Cancer Prediction)

## Overview

This project implements a complete machine learning pipeline for binary classification using the Breast Cancer dataset. The goal is to classify tumors as malignant (0) or benign (1) using Logistic Regression.

The pipeline includes preprocessing, dimensionality reduction (PCA), model training, evaluation using multiple metrics, and visualization through various performance curves.

---

## Workflow

1. Data Loading
2. Train-Test Split
3. Feature Scaling (Standardization)
4. Dimensionality Reduction using PCA
5. Model Training (Logistic Regression)
6. Model Evaluation (metrics + plots)
7. Threshold Tuning

---

## Evaluation Metrics

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score

These metrics provide a better understanding of model performance, especially for medical datasets where false negatives are critical.

---

## Visualizations Included

The project includes the following important plots:

* Confusion Matrix
* ROC Curve
* Precision-Recall Curve
* Threshold vs Precision-Recall Curve
* Train vs Test ROC Curve
* Learning Curve (to check overfitting/underfitting)
* Actual vs Predicted Probability Plot

These plots help in understanding model behavior and decision-making.

---

## Key Concepts Used

### Logistic Regression

A linear model used for binary classification that outputs probabilities using the sigmoid function.

### PCA (Principal Component Analysis)

Used to reduce dimensionality and remove noise while retaining important information.

### Threshold Tuning

Instead of using the default 0.5 threshold, the decision boundary can be adjusted (e.g., 0.3) to improve recall in critical applications like cancer detection.

---

## Important Insight

Accuracy alone is not sufficient for evaluating classification models, especially in healthcare scenarios.

In this project, recall is prioritized to minimize false negatives (i.e., missing actual cancer cases).

---

## Technologies Used

* Python
* NumPy
* Matplotlib
* Scikit-learn

---

## Results Interpretation

* If train and test accuracy are similar → model generalizes well
* If train accuracy is much higher → overfitting
* ROC curve closer to top-left → better model
* Precision-Recall curve helps in imbalanced scenarios

---

## Future Improvements

* Hyperparameter tuning (GridSearchCV)
* Use of Pipeline for cleaner workflow
* Compare with other models (SVM, Random Forest)
* Apply on custom datasets

---

## Conclusion

This project demonstrates a complete and structured approach to solving a binary classification problem using Logistic Regression. It emphasizes proper evaluation, visualization, and practical decision-making through threshold tuning.

---
