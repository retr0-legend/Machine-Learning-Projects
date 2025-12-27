# Heart Disease Analysis & Prediction Project

This project explores a comprehensive heart disease dataset to perform predictive modeling using both classification and regression techniques. The goal is to identify key risk factors and accurately predict heart attack outcomes.

## Dataset Overview
The dataset (`heart_diseasee.csv`) contains patient information including:
* [cite_start]**Demographics**: Country, Gender, Education Level, Income Level. [cite: 2]
* [cite_start]**Clinical Metrics**: Cholesterol levels (HDL, LDL, Triglycerides), Blood Pressure, Max Heart Rate. [cite: 2]
* [cite_start]**Lifestyle Factors**: Smoking History, Alcohol Consumption, Physical Activity, Stress Levels. [cite: 2]
* [cite_start]**Target Variable**: `Heart_Attack_Outcome` (Binary: 0 or 1). [cite: 2]

## Project Structure
- [cite_start]`alisha_classification.ipynb`: Implements multiple classification models to predict heart attack outcomes. 
- [cite_start]`tayyba_regression.ipynb`: Focuses on regression analysis and feature relationships. 
- [cite_start]`heart_diseasee.csv`: The raw dataset used for training and testing. [cite: 2]

## Machine Learning Models
The classification notebook evaluates the following algorithms:
* [cite_start]Logistic Regression 
* [cite_start]Gaussian Naive Bayes 
* [cite_start]Support Vector Classifier (SVC) 
* [cite_start]Decision Tree & Random Forest Classifiers 

## Key Features
- [cite_start]**Data Preprocessing**: Handling categorical variables using `LabelEncoder` and scaling features with `StandardScaler`. [cite: 1, 5]
- [cite_start]**Dimensionality Reduction**: Implementation of PCA (Principal Component Analysis). 
- [cite_start]**Evaluation**: Performance is measured using Confusion Matrices and Classification Reports (Precision, Recall, F1-Score). 

## Setup and Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/retr0-legend/Machine-learning-projects.git](https://github.com/retr0-legend/Machine-learning-projects.git)
