# Comparative-Analysis-of-ML-Algorithms-Predicting-Hospital-Readmission-of-Diabetes-Patients
This is my Capstone Project at Minerva University.

This project presents a comprehensive comparative analysis of various machine learning (ML) algorithms to predict hospital readmission among Type 2 diabetes patients. Utilizing a rich dataset from "Diabetes 130-US hospitals for years 1999-2008," we meticulously cleaned, preprocessed, and applied feature selection techniques to enhance model performance. We evaluated Random Forest, Naive Bayes, K-Nearest Neighbors (KNN), XGBoost, Convolutional Neural Network (CNN), and a novel approach combining CNN with genetic algorithm-based optimization (GA-CNN) across metrics such as accuracy, precision, recall, F1-score, and AUC.

## Dataset
The dataset used in this project is the "Diabetes 130-US hospitals for years 1999-2008" dataset, available from the UCI Machine Learning Repository. It includes data on hospital admissions, patient demographics, diagnostic codes, medications, and readmission information.

## Project Structure

- **Data Cleaning and Preprocessing:** Preliminary cleaning, handling missing values and duplicates, and outliers treatment.
- **Feature Engineering:** Encoding, scaling, and generating new features from existing data.
- **Feature Selection:** Employing various methods like Chi-squared, Mutual Information, ANOVA, Recursive Feature Elimination (RFE), and Lasso to identify significant features.
- **Model Implementation:** Detailed implementation of Random Forest, Naive Bayes, KNN, XGBoost, CNN, and GA-CNN models, including hyperparameter tuning and evaluation.
- **Results Interpretation:** Utilizing SHAP analysis to interpret model predictions and identify key predictors of hospital readmission.

## Key Findings

- **Feature Importance:** Identified crucial features influencing hospital readmission risks, such as the number of inpatient visits, lab procedures, medications, and patient demographics.
- **Model Performance:** XGBoost and Random Forest models demonstrated the highest accuracy and reliability in predicting hospital readmissions.
- **Interpretability:** SHAP analysis provided insights into the impact of patient characteristics on readmission risks, highlighting the importance of comprehensive patient histories and condition management.


