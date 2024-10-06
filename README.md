# Heart Disease Prediction using Logistic Regression

This project implements a simple heart disease prediction system using Logistic Regression. The model is trained on the well-known Heart Disease dataset, which contains various health indicators such as age, cholesterol levels, and blood pressure to predict whether a patient has heart disease or not.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Workflow](#project-workflow)
- [Model Performance](#model-performance)
- [How to Use](#how-to-use)
- [Libraries Used](#libraries-used)

## Introduction

Heart disease is one of the leading causes of death globally. This project aims to develop a simple and interpretable machine learning model that predicts the likelihood of a person having heart disease based on health-related factors. The model uses Logistic Regression, a widely used classification algorithm that is particularly useful for binary outcomes such as this one.

## Dataset

The dataset used in this project is the Heart Disease dataset containing features like:

### Dataset Overview

The dataset consists of the following features:
- **Age:** Age of the patient (in years).
- **Sex:** Gender of the patient (1 = male, 0 = female).
- **Cp (Chest Pain Type):** Chest pain type experienced, with values:
  - 0: Asymptomatic
  - 1: Atypical Angina
  - 2: Non-Anginal Pain
  - 3: Typical Angina
- **Trestbps (Resting Blood Pressure):** The resting blood pressure of the patient (measured in mm Hg).
- **Chol (Serum Cholesterol):** Cholesterol levels (measured in mg/dl).
- **Fbs (Fasting Blood Sugar):** Whether the patient’s fasting blood sugar is >120 mg/dl (1 = true, 0 = false).
- **Restecg (Resting ECG Results):** Results of the resting electrocardiographic exam, represented as:
  - 0: Normal
  - 1: Having ST-T wave abnormality
  - 2: Showing left ventricular hypertrophy.
- **Thalach (Maximum Heart Rate Achieved):** Maximum heart rate during physical exertion.
- **Exang (Exercise-Induced Angina):** Whether the patient experiences angina during exercise (1 = yes, 0 = no).
- **Oldpeak (ST Depression Induced by Exercise):** ST depression relative to rest, a measure of heart stress.
- **Slope (Slope of the Peak Exercise ST Segment):**
  - 0: Upsloping
  - 1: Flat
  - 2: Downsloping.
- **Ca (Number of Major Vessels Colored by Fluoroscopy):** Ranges from 0 to 3, indicating the number of vessels visible.
- **Thal (Thalassemia):** Blood disorder diagnosis, coded as:
  - 0: Normal
  - 1: Fixed Defect
  - 2: Reversible Defect.
- **Target:** The target label indicating the presence of heart disease (1 = heart disease, 0 = no heart disease).

## Project Workflow

1. **Data Loading:** The dataset is uploaded and loaded into a pandas DataFrame.
2. **Data Exploration:**
   - Summary statistics are displayed to understand the distribution of features.
   - Checking for missing values.
3. **Data Preprocessing:** Features (X) are separated from the target (Y). The dataset is split into training and testing sets using an 80-20 split.
4. **Model Training:** A Logistic Regression model is trained on the training data.
5. **Model Evaluation:** The model's performance is evaluated on both the training and test sets using accuracy scores.
6. **Prediction System:** A simple predictive system is built, where a user can input their health metrics to predict whether they are likely to have heart disease.

## Model Performance

- **Training Accuracy:** ~ (replace with actual accuracy)
- **Testing Accuracy:** ~ (replace with actual accuracy)

## How to Use

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/heart-disease-prediction.git
