# Student Performance Prediction

Regression-based analysis and prediction of student performance using Python.

## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pandas,numpy,sklearn,jupyter,vscode" />
</p>

## 📌 Project Overview

This project uses Multiple Linear Regression to predict the Performance Index of students based on their study habits and academic factors.

Three regression models were developed and compared:

- Basic Multiple Linear Regression
- MLR with a Quadratic Term
- MLR with an Interaction Term

## 📊 Dataset

The dataset contains 499 student records with the following variables:

- Hours Studied
- Previous Scores
- Extracurricular Activities
- Sleep Hours
- Sample Question Papers Practiced
- Performance Index

## 🎯 Objectives

- Develop a Basic Multiple Linear Regression model.
- Evaluate the model using R², Adjusted R², MAE, MSE, and RMSE.
- Add a quadratic term and evaluate the polynomial model.
- Add an interaction term and evaluate the interaction model.
- Compare the performance of all three models.
- Predict the Performance Index for a given student.

## 🤖 Model Development

### Model 1 — Basic Multiple Linear Regression

The initial model uses all five independent variables to predict the Performance Index.

### Model 2 — MLR with Quadratic Term

A quadratic term for `Hours Studied` was added to the model to check whether a non-linear relationship improves prediction.

### Model 3 — MLR with Interaction Term

An interaction term between `Hours Studied` and `Previous Scores` was added to check whether the effect of one variable depends on the other.

## 📈 Model Comparison

| Model | R² | Adjusted R² | RMSE |
|---|---:|---:|---:|
| Basic MLR | 0.9889 | 0.9883 | 2.0788 |
| MLR with Quadratic Term | 0.9887 | 0.9880 | 2.0958 |
| MLR with Interaction Term | 0.9889 | 0.9882 | 2.0805 |

The **Basic Multiple Linear Regression** model performed slightly better based on the comparison of R², Adjusted R², and RMSE.

## 🔮 Prediction

The models were used to predict the Performance Index for a student with the following values:

| Feature | Value |
|---|---:|
| Hours Studied | 8 |
| Previous Scores | 85 |
| Extracurricular Activities | Yes |
| Sleep Hours | 7 |
| Sample Question Papers Practiced | 6 |

### Prediction Results

| Model | Predicted Performance Index |
|---|---:|
| Basic MLR | 80.46 |
| Quadratic Model | 80.52 |
| Interaction Model | 80.49 |

The **Basic MLR** was selected as the final model.

**Final Predicted Performance Index: 80.46**

## 👤 Author

**Soham Shirode**