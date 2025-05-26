# Assignment 3 – Regression & Logistic Modeling

This assignment focuses on **linear and logistic regression**, residual diagnostics, and model comparison.

## 📌 Part 1: Linear Regression

- Fit 2 linear models to predict median house value using `housing.csv`
- Check:
  - Collinearity using **VIF**
  - Heteroscedasticity using **residual plots** and `ncvTest()`
  - Normality via **Q-Q plot**
- Compare models using **AIC**
- Report best model coefficients with **confidence intervals**

## 📌 Part 2: Logistic Regression

- Predict admission (1/0) using **GRE, GPA, and undergrad rank**
- Fit logistic regression using `binary.csv`
- Interpret coefficients using **odds ratios**
- Include interaction effect: **GPA × Rank**

## 📁 Files

- `brsm_regression_assignment_2021102016.ipynb`: Python/R analysis notebook
- `RegressionAssignmentBRSM.pdf`: Problem statement
- `brsm_regression_assignment_2021102016.pdf`: Final report
- `housing.csv`: Housing dataset
- `binary.csv`: Admissions dataset
