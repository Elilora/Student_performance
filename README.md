# Student Performance Analysis

This project is a Multiple Linear Regression project which involves analyzing student performance data to understand the factors influencing academic success. It includes data preprocessing, exploratory data analysis, model building, and fine-tuning. Here's a breakdown of the steps involved:

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Data Loading](#data-loading)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Building](#model-building)
- [Fine Tuning and Evaluation](#fine-tuning-and-evaluation)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction

The project aims to analyze student performance data to identify the key factors affecting academic outcomes. It involves building multi-linear regression models to predict performance indexes based on various features such as hours studied, previous scores, extracurricular activities, sleep hours, and sample question papers practiced.

## Installation

```bash
      pip install numpy pandas seaborn matplotlib scikit-learn
```
## **Data Loading**
The student performance data is loaded from a CSV file located in the Data folder.

## **Data Preprocessing**
Data preprocessing involves checking for data quality and tidness issues like  missing values and duplicates, handling categorical data, and scaling numeric features using StandardScaler.

## **Exploratory Data Analysis**
Exploratory data analysis includes analyzing the distribution of features, correlation analysis, outlier detection, and visualizations using boxplots and histograms.

## **Model Building**
Regression models (Linear Regression, Ridge Regression, Lasso Regression) are built using pipeline objects to predict performance indexes. The data is split into training and testing sets for model evaluation.( 70 -30)

## **Fine Tuning and Evaluation**
Hyperparameter tuning is performed using GridSearchCV for Ridge and Lasso regression models. The tuned models are evaluated using performance metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R2 Score.

## **Results**
The results of the regression models are displayed, including intercepts, coefficients, and evaluation metrics. Visualizations such as scatter plots, residual plots, and coefficient plots are generated to analyze model performance.

## **Conclusion*8
The project provides insights into the factors influencing student performance and demonstrates the effectiveness of regression models in predicting academic outcomes.

## **Contributing**
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.



