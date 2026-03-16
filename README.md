Stroke Prediction Using Machine Learning
Project Overview

This project focuses on predicting the likelihood of stroke using machine learning techniques. Stroke is a serious medical condition, and early prediction can assist healthcare professionals in identifying high-risk individuals and taking preventive measures.

The project applies data analysis, data preprocessing, and machine learning models to analyze health-related features and predict whether a patient is likely to experience a stroke.

Problem Statement

Stroke is one of the leading causes of death and disability worldwide. Early detection and risk assessment are critical for prevention and treatment. This project aims to develop a predictive model that can estimate stroke risk based on patient health data.

Dataset

The dataset used in this project contains health-related information about individuals. The features include demographic, lifestyle, and medical attributes.

Key Features in the Dataset

Age

Gender

Hypertension

Heart Disease

Average Glucose Level

Body Mass Index (BMI)

Smoking Status

Work Type

Residence Type

Stroke (Target Variable)

The target variable indicates whether a person has experienced a stroke (1) or not (0).

Project Workflow

The project followed these main steps:

Dataset → Data Cleaning → Data Preprocessing → Exploratory Data Analysis → Model Training → Model Evaluation

Data Cleaning and Preprocessing

Several preprocessing steps were performed to prepare the dataset for machine learning:

Handling missing values

Encoding categorical variables

Feature selection

Splitting the dataset into training and testing sets

Addressing class imbalance using class weighting and SMOTE

Exploratory Data Analysis (EDA)

EDA was performed to understand patterns and relationships within the dataset.

Techniques used include:

Count plots

Correlation heatmaps

Distribution analysis

These visualizations helped identify important features related to stroke occurrence.

Handling Class Imbalance

The dataset contained significantly more non-stroke cases than stroke cases. To address this issue:

Class weighting was applied

SMOTE (Synthetic Minority Oversampling Technique) was used

This helped improve the model's ability to detect stroke cases.

Machine Learning Models

Several machine learning algorithms were tested to determine the best performing model.

Algorithms Used

Logistic Regression

Decision Tree

Random Forest

Multiple models were trained and evaluated using performance metrics to determine the most suitable model for stroke prediction.

Model Evaluation

The models were evaluated using the following metrics:

Accuracy

Precision

Recall

F1 Score

ROC-AUC Score

Confusion Matrix

These metrics help measure the effectiveness of each model in predicting stroke risk.

Key Insights

Class imbalance significantly affects prediction performance.

Logistic Regression performed well in detecting stroke cases with high recall.

Tree-based models achieved high accuracy but struggled to detect minority stroke cases.

Conclusion

Machine learning techniques can assist in predicting stroke risk based on health data. Predictive models can support healthcare professionals in early detection and decision-making, potentially improving patient outcomes.

Future Improvements

Use larger and more diverse healthcare datasets

Test additional algorithms such as XGBoost and Gradient Boosting

Improve feature engineering

Deploy the model as a web application for real-time predictions

Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Jupyter Notebook
