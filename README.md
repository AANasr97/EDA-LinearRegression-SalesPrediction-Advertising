# ISLR_Advertising


# Project Name: EDA | Sales Prediction | ISLR Advertising

## Overview

This project explores various regression techniques using the SciKit-Learn library. It covers Simple Linear Regression, Polynomial Regression, Regularization (L2 Ridge and L1 Lasso), and Elastic Net Regression. The goal is to predict sales based on different advertising channels (TV, Radio, Newspaper) and analyze the model performance.

## Prerequisites

Make sure you have the following libraries installed before running the code:

- Pandas
- Numpy
- Statsmodels
- Matplotlib
- Plotly Express
- Seaborn
- Scikit-Learn
- Joblib


## Usage

The project is divided into several sections, each exploring a different aspect of regression analysis. Here's a brief overview of what each section covers:

### Simple Linear Regression

- Investigates the relationship between total advertising spend and sales.
- Performs data analysis and visualization.
- Implements a Simple Linear Regression model.
- Evaluates the model's performance.

### Polynomial Regression

- Extends the analysis to Polynomial Regression.
- Explores higher degree polynomial features.
- Evaluates model performance with different polynomial degrees.

### Regularization with Ridge and Lasso

- Introduces regularization techniques to handle overfitting.
- Implements Ridge (L2) and Lasso (L1) Regression.
- Chooses optimal alpha values using cross-validation.
- Evaluates the models and compares their performance.

### Elastic Net Regression

- Combines Ridge and Lasso penalties in Elastic Net Regression.
- Selects the best L1 ratio and alpha values.
- Evaluates the Elastic Net model's performance.

## Data

The project uses the "Advertising.csv" dataset, which contains information about advertising spending and sales. The dataset is provided in the project files.

## Deployment

The project also includes model deployment for predictions. Models are saved using Joblib and can be loaded for making predictions on new data.