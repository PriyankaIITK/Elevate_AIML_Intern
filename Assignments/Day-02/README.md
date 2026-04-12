# Task 2: Exploratory Data Analysis

## Overview

In this task, I performed exploratory data analysis on the Titanic dataset to understand the structure of the data and identify patterns related to passenger survival.

## Objective

The main objective was to analyze the dataset using basic statistical methods and visualizations, and to understand relationships between different features.

## Tools Used

Python, Pandas, Matplotlib, Seaborn

## Files Included

* titanic_eda.ipynb / .py – contains the EDA code
* Titanic-Dataset.csv – dataset used for analysis

## Steps Performed

1. Data Loading
   The dataset was uploaded and read using Pandas.

2. Data Understanding
   I checked the shape of the dataset, column names, and data types, and viewed the first few rows.

3. Handling Missing Values
   Missing values in the Age column were filled using the median, and missing values in Embarked were filled using the mode. The Cabin column was removed due to a large number of missing values.

4. Statistical Analysis
   Summary statistics such as mean, median, and standard deviation were generated to understand the distribution of numerical features.

5. Data Visualization
   Different plots were used to analyze the data:

* Histograms to understand distribution
* Boxplots to detect outliers
* Count plots for categorical variables
* Scatter plots to study relationships between features
* Heatmap to analyze correlation between variables

## Observations

From the analysis, it was observed that survival was influenced by factors such as gender, passenger class, and fare. Female passengers and those in higher classes had better chances of survival.

## Conclusion

This analysis helped in understanding the dataset and identifying important features that affect survival. These insights can be useful for further modeling and prediction tasks.

