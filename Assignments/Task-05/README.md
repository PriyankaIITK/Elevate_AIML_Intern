# Decision Trees & Random Forests – Heart Disease Prediction

## Overview

This project focuses on implementing tree-based machine learning models for classification using a heart disease dataset.
The goal is to understand how Decision Trees and Random Forests work, compare their performance, and interpret results.

---

## Objective

* Learn Decision Tree Classifier
* Understand and control overfitting
* Implement Random Forest
* Compare model performance
* Analyze feature importance
* Evaluate models using cross-validation

---

## Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## Dataset

* File used: `heart.csv`
* Contains medical attributes such as age, cholesterol, blood pressure, etc.
* Target column:

  * `1` → Disease present
  * `0` → No disease

---

## Steps Performed

### 1. Data Loading & Preprocessing

* Loaded dataset using Pandas
* Split into features (`X`) and target (`y`)
* Performed train-test split (80-20)

---

### 2. Decision Tree Model

* Trained a basic Decision Tree classifier
* Evaluated accuracy and classification report

---

### 3. Overfitting Control

* Limited tree depth using `max_depth`
* Compared performance with and without restriction

---

### 4. Tree Visualization

* Visualized decision tree structure using `plot_tree`
* Helps understand how decisions are made

---

### 5. Random Forest Model

* Trained Random Forest with multiple trees
* Compared accuracy with Decision Tree

---

### 6. Feature Importance

* Extracted most important features
* Visualized their contribution

---

### 7. Cross Validation

* Applied 5-fold cross-validation
* Ensured model reliability and stability

---

## Results Summary

* Decision Trees are simple but prone to overfitting
* Controlled trees perform better than fully grown ones
* Random Forest gives better accuracy and more stable predictions
* Feature importance helps identify key health factors

---

## Output

* Accuracy scores for both models
* Classification reports
* Decision tree visualization
* Feature importance graph
* Cross-validation scores

---

## Key Learnings

* Tree-based models are easy to interpret
* Depth control is crucial to avoid overfitting
* Ensemble methods improve performance
* Cross-validation ensures model robustness

---

## Future Improvements

* Hyperparameter tuning (GridSearchCV)
* Try Gradient Boosting / XGBoost
* Add more visualizations (ROC curve, confusion matrix)

---

## Author

Priyanka
