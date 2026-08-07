# House Pricing Data Analysis

## Overview

This project analyzes residential housing data from King County, Washington, to identify factors associated with home prices and build predictive regression models.

The project was completed as part of IBM's **Data Analysis with Python** course and demonstrates an end-to-end data analysis and model development workflow using Python.

## Objectives

- Explore and clean residential housing data
- Identify features associated with house prices
- Visualize relationships and potential outliers
- Build linear regression models for price prediction
- Evaluate model performance using R²
- Apply polynomial feature transformations
- Use Ridge regression to reduce overfitting and improve model generalization

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Analysis

### Data Preparation
- Inspected column data types and descriptive statistics
- Removed unnecessary columns
- Identified and handled missing values
- Examined distributions of housing characteristics

### Exploratory Data Analysis
- Analyzed the relationship between living area and house price
- Compared waterfront and non-waterfront properties
- Examined price outliers using box plots
- Evaluated correlations between numerical housing features and price

### Model Development
Multiple regression approaches were evaluated:

- Simple Linear Regression
- Multiple Linear Regression
- Polynomial Regression
- Ridge Regression
- Scikit-learn Pipelines

Features such as living area, bedrooms, bathrooms, floors, waterfront status, location, and other property characteristics were used to predict house prices.

## Model Evaluation

Models were evaluated primarily using the **R² score** to measure how much variation in house prices could be explained by the selected features.

The project also uses train/test splitting and Ridge regularization to evaluate model performance on unseen data and reduce the risk of overfitting.

## Repository Structure

```text
House-Pricing-Data-Analysis/
│
├── House_Sales_in_King_Count_USA.ipynb
├── README.md
