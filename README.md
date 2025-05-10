# 🩺 Insurance Cost Prediction Project

This project performs an end-to-end data analysis and predictive modeling workflow on a health insurance cost dataset using Python. It is designed to demonstrate practical skills in EDA, regression modelling, and feature engineering.

---

## 📌 Objectives

- Load and explore a health insurance dataset
- Clean the data (handle missing or inconsistent entries)
- Conduct exploratory data analysis (EDA) to understand key cost drivers
- Build:
  - Single-variable Linear Regression models
  - Multi-variable Linear Regression models
  - Ridge Regression models for regularisation
- Evaluate and compare model performance

---

## 🗂 Dataset

The dataset (`insurance.csv`) contains the following fields:
- `age`: age of primary beneficiary
- `sex`: insurance contractor gender
- `bmi`: Body Mass Index
- `children`: number of dependents
- `smoker`: smoking status
- `region`: residential region in the U.S.
- `charges`: individual medical costs billed by health insurance

---

## 📊 Exploratory Data Analysis

Visualisations and correlation analysis were conducted to identify features that most impact insurance charges, particularly:

- Age
- BMI (especially for smokers)
- Smoking status
- Number of children


---

## 🧠 Modeling Approach

1. **Single-variable Linear Regression**:
   - Target: `charges`
   - Predictors: individual features like `age`, `bmi`, `smoker`

2. **Multi-variable Linear Regression**:
   - Predictors: all features, with categorical variables encoded

3. **Ridge Regression**:
   - Applied to reduce overfitting and improve model generalisation


## 🧪 Model Performance

| Model                 | R² Score |
|----------------------|----------|
| Single-variable (age) | 0.xx     |
| Multi-variable        | 0.xx     |
| Ridge Regression      | 0.xx     |

---

## 📦 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt

