# University-Dropout-Prediction-Model

This project aims to predict student dropout rates from post-secondary institutions using various statistical and machine learning techniques. The dataset contains information on academic performance, financial status, and demographic characteristics of students. The goal is to build a high-accuracy predictive model that can forecast whether a student is likely to drop out based on these factors.

## Table of Contents:

[Introduction]()

[Dataset]()

[Project Workflow]()

1. Data Preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Model Development
5. Model Evaluation
6. Predictive Analysis

[Results]()

[Conclusion]()


## Introduction
This project explores the factors contributing to student dropout rates and leverages machine learning to predict student outcomes. The key objectives include performing statistical analyses, developing a predictive model, and deriving insights to support interventions aimed at reducing dropout rates.

## Dataset
The dataset contains the following key features:

Academic Performance: Grades achieved in various classes, total credits completed, curricular units approved, etc.
Financial Status: Debt, scholarship provision, tuition fee payment status, etc.
Demographic Characteristics: Age at enrollment, gender, etc.
Student Status: Target variable indicating whether the student dropped out, is still enrolled, or graduated.

## Project Workflow
1. Data Preprocessing - Handling missing values, removing duplicates, and ensuring data consistency. Standardizing numerical features and encoding categorical variables.

2. Exploratory Data Analysis (EDA)

Correlation Analysis - Used Pearson correlation to explore linear relationships between 'Student Status' and other features. Applied Spearman's rank correlation to identify non-linear relationships. Visualization: Created bar charts, histograms, and box plots to understand the distribution and impact of key features on student status.

3. Feature Engineering - Interaction Features: Engineered interaction terms between first and second semester grades to capture combined effects. Aggregated Features: Created summary features, such as total approved curricular units, to reflect cumulative academic achievements.

4. Model Development - Model Selection: Evaluated multiple machine learning models, including Gradient Boosting, Random Forest, Logistic Regression, SVM, and KNN. Dimensionality Reduction: Implemented Principal Component Analysis (PCA) to reduce dimensionality while retaining maximum variance. Pipeline Configuration: Set up pipelines with preprocessing steps, model-specific hyperparameters, and cross-validation.

5. Model Evaluation - Hyperparameter Tuning: Performed RandomizedSearchCV to optimize model parameters. Performance Metrics: Assessed models using accuracy, precision, recall, and F1-score.

6. Predictive Analysis - Prediction: Used the final tuned model to predict student dropout likelihood based on new data. Insights: Provided actionable insights based on model predictions to inform intervention strategies.

## Results
Achieved a high accuracy in predicting student dropout rates. Identified key factors influencing student dropout, including academic performance, financial status, and demographic characteristics.

## Conclusion
This project successfully demonstrated the use of statistical analysis and machine learning to predict student dropout rates. The insights gained from this analysis can help educational institutions identify at-risk students and implement targeted interventions.

