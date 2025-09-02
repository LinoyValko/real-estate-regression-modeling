# Real Estate Valuation – Regression Modeling Project
---

## Project Description

This assignment focuses on **predicting real estate prices** using machine learning regression models.  
The dataset includes features of properties in Taipei, Taiwan, such as house age, distance from the nearest MRT station, number of convenience stores, and more.

The project includes the following steps:

- Data loading & preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature engineering & correlation analysis  
- Regression modeling (Linear Regression, Lasso, Ridge, etc.)  
- Hyperparameter tuning  
- Result interpretation & conclusion

---

## Dataset Overview

- Source: [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/Real+estate+valuation+data+set)
- Format: Excel `.xlsx`
- Number of instances: 414  
- Number of features: 7

| Feature                          | Description                                     |
|----------------------------------|-------------------------------------------------|
| X1 transaction date              | (year/month)                                    |
| X2 house age                     | Age of the house in years                       |
| X3 distance to the nearest MRT  | In meters                                       |
| X4 number of convenience stores | Count of nearby stores                          |
| X5 latitude                      | Geographic coordinate                           |
| X6 longitude                     | Geographic coordinate                           |
| Y house price of unit area      | **Target variable** – price per square meter    |

---

## Models and Techniques Used

- **Linear Regression**
- **Lasso Regression**
- **Ridge Regression**
- GridSearchCV for hyperparameter tuning
- Correlation matrix and multicollinearity analysis

---

## Results Summary

- Best model: **Ridge Regression with tuned alpha**
- Performance metrics:
  - R² Score
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
- Feature importance analysis conducted for interpretability

---

## How to Run

1. Clone or download this repository
2. Install required packages:
```bash
pip install pandas matplotlib seaborn scikit-learn openpyxl



