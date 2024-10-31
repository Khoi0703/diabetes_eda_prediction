# Diabetes Prediction Project

## Overview
This project aims to build a machine learning model to predict the onset of diabetes using a dataset containing medical diagnostic measurements from female patients. The project involves data exploration, cleaning, and model training.

## Dataset
The dataset contains 768 records with the following attributes:
- **Pregnancies**: Number of pregnancies
- **Glucose**: Plasma glucose concentration
- **BloodPressure**: Diastolic blood pressure
- **SkinThickness**: Triceps skinfold thickness
- **Insulin**: 2-hour serum insulin
- **BMI**: Body Mass Index
- **DiabetesPedigreeFunction**: Family history of diabetes
- **Age**: Age of the patient
- **Outcome**: Presence of diabetes (1) or not (0)

## EDA (Exploratory Data Analysis)
The analysis includes:
- Correlation analysis between features.
- Distribution visualizations using KDE plots.
- Boxplots and line charts to identify trends.

## Model Building
- Utilized **Logistic Regression** as the primary classification algorithm.
- Performed hyperparameter tuning to find the best parameters (C=10, solver='liblinear').
- Evaluated model performance with accuracy, confusion matrix, and classification report.

## Requirements
- Python 3.x
- Libraries: pandas, numpy, scikit-learn, seaborn, matplotlib
---

