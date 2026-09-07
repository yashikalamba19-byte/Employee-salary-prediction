# Employee Salary Prediction

## 📌 Project Overview

This project uses Machine Learning regression techniques to predict an employee's monthly salary based on different employee-related features.

The project includes data cleaning, exploratory data analysis (EDA), categorical encoding, feature scaling, model training, evaluation, and salary prediction.

## 🎯 Objective

To build a Machine Learning model that can predict an employee's monthly salary using factors such as age, education level, experience, job role, department, location, certification, performance score, and company size.

## 📊 Dataset Features

The dataset contains the following features:

- Age
- Education Level
- Years of Experience
- Job Role
- Department
- Location
- Certification
- Performance Score
- Company Size
- Salary — Target Variable

**Target Variable:** Salary (Monthly Salary in INR)

## 🔍 Exploratory Data Analysis

The project performs EDA to understand:

- Salary distribution
- Age and experience distribution
- Education level distribution
- Job role and department distribution
- Salary variation across locations
- Salary variation by education and job role
- Relationship between experience and salary
- Relationship between performance score and salary
- Effect of certification and company size on salary

## 🧹 Data Preprocessing

The following preprocessing techniques were performed:

- Handling missing values
- Categorical feature encoding
- Ordinal encoding for ordered categories
- One-hot encoding for nominal categories
- Label encoding where appropriate
- Feature scaling
- Train-test split

## 🤖 Machine Learning Models

Three regression models were evaluated:

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor

## 📈 Model Evaluation

The models were evaluated using regression metrics including:

- Mean Absolute Error (MAE)
- R² Score

The model with the best performance was selected for salary prediction.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Jupyter Notebook

## 📁 Project Structure

```text
employee-salary-prediction/
│
├── Employee_Salary.ipynb
├── README.md
└── employee_salary_dataset.csv

## Workflow

Data Collection
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
Feature Encoding
      ↓
Feature Scaling
      ↓
Train-Test Split
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Salary Prediction

## Author

Yashika Lamba
