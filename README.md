# Student Performance Analysis (R)

## Overview
This is a group project and we analyze student academic performance using the **Student Performance dataset** from the **UCI Machine Learning Repository**.  
The goal is to **predict final course grades (G3)** and identify key academic, behavioral, and background factors that influence student outcomes.

The analysis focuses on the **Portuguese subject**, which provides a larger and more stable sample, and demonstrates an end-to-end data analytics workflow from exploratory analysis to model comparison.

**Live HTML Output (GitHub Pages)**  : [Link](https://yoora07-ai.github.io/R/)

---

## Methods
- Data cleaning and preprocessing (no missing values)
- Exploratory Data Analysis (EDA)
  - Correlation analysis for numeric variables
  - ANOVA for categorical variables
- Feature selection based on statistical significance
- Model development and comparison:
  - Linear Regression
  - Ridge Regression
  - Random Forest
- Model evaluation using **Test Mean Squared Error (MSE)**

---

## Key Results
- **Ridge Regression** achieved the best predictive performance  
  - **Test MSE: 6.72**
- Strongest predictors of final grades:
  - Number of past class failures
  - Aspiration for higher education
- Regularization effectively handled multicollinearity among predictors

---

## Tech Stack
- **R**
- `dplyr`, `ggplot2`
- `glmnet`, `randomForest`

---

## Takeaway
Academic history and educational aspirations are the strongest drivers of student performance, while behavioral and background factors play a secondary but meaningful role. Regularized models provide superior predictive accuracy when predictors are correlated.

---

