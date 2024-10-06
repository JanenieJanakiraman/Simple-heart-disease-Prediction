__Heart Disease Prediction using Logistic Regression__

This project implements a simple heart disease prediction system using Logistic Regression. The model is trained on the well-known Heart Disease dataset, which contains various health indicators such as age, cholesterol levels, and blood pressure to predict whether a patient has heart disease or not.
Table of Contents

Introduction
Dataset
Project Workflow
Model Performance
How to Use
Libraries Used
Introduction

Heart disease is one of the leading causes of death globally. This project aims to develop a simple and interpretable machine learning model that predicts the likelihood of a person having heart disease based on health-related factors.
The model uses Logistic Regression, a widely used classification algorithm that is particularly useful for binary outcomes such as this one.
Dataset

The dataset used in this project is the Heart Disease dataset containing features like:
Age
Gender
Resting blood pressure
Cholesterol levels
Maximum heart rate
And more...
The target variable is:
1: The patient has heart disease (positive)
0: The patient does not have heart disease (negative)
Project Workflow

Data Loading: The dataset is uploaded and loaded into a pandas DataFrame.
Data Exploration:
Summary statistics are displayed to understand the distribution of features.
Checking for missing values.
Data Preprocessing: Features (X) are separated from the target (Y). The dataset is split into training and testing sets using an 80-20 split.
Model Training: A Logistic Regression model is trained on the training data.
Model Evaluation: The model's performance is evaluated on both the training and test sets using accuracy scores.
Prediction System: A simple predictive system is built, where a user can input their health metrics to predict whether they are likely to have heart disease.
Model Performance

Training Accuracy: ~ (replace with actual accuracy)
Testing Accuracy: ~ (replace with actual accuracy)
How to Use

**Clone the repository:**


git clone https://github.com/yourusername/heart-disease-prediction.git


__Install required libraries:__

pip install -r requirements.txt


Upload the heart_disease_data.csv dataset or use a similar dataset.
Run the Python script or Jupyter notebook to train the model and make predictions.


**Libraries Used**

NumPy
pandas
scikit-learn
