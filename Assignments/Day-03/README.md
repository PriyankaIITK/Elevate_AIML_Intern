# House Price Prediction using Linear Regression

## Overview

This project focuses on predicting house prices using a Machine Learning approach. The model is built using Linear Regression and trained on a housing dataset. The workflow includes data preprocessing, feature encoding, model training, evaluation, and visualization of results.

---

## Objectives

* To build a regression model for predicting house prices
* To preprocess real-world data for machine learning
* To evaluate model performance using standard regression metrics
* To visualize predictions and model behavior

---

## Dataset

The dataset used in this project contains housing-related features such as:

* Area
* Number of bedrooms and bathrooms
* Parking availability
* Furnishing status
* Other categorical attributes

Target variable:

* **Price**

---

## Methodology

### 1. Data Preprocessing

* Converted categorical features into numerical format using one-hot encoding
* Handled missing values using mean imputation
* Standardized features using StandardScaler

### 2. Train-Test Split

* Dataset divided into training (80%) and testing (20%) sets

### 3. Model Training

* Applied Linear Regression using sklearn
* Model trained on scaled feature set

### 4. Evaluation Metrics

The model was evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

---

## Results

### Training Performance

* MAE: 719242.89
* MSE: 9.68 × 10¹¹
* R² Score: 0.686

### Testing Performance

* MAE: 970043.40
* MSE: 1.75 × 10¹²
* R² Score: 0.653

---

## Interpretation

* The model explains approximately 65% of the variance in house prices
* Train and test scores are close, indicating no overfitting
* Moderate error values suggest the model can be improved further

---

## Visualizations

* Scatter plot of Actual vs Predicted Prices
* Learning curve showing Train vs Test Error

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## Future Improvements

* Use advanced models such as Random Forest or Gradient Boosting
* Apply feature engineering techniques
* Perform hyperparameter tuning
* Explore non-linear relationships

---

## Conclusion

This project demonstrates a complete machine learning pipeline for house price prediction using Linear Regression. While the model provides reasonable performance, there is scope for improvement using more advanced techniques.
