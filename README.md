# Project-Data-Mining-Predicting-Student-Performance-Using-Machine-Learning-Classification-Models-2024

This repository presents a research-based machine learning pipeline for predicting students’ academic performance using classification algorithms. The project explores various supervised models, evaluates key predictors, and analyzes the effects of data preprocessing to support data-driven educational interventions.

# Overview
With the increasing adoption of digital education systems, early prediction of student academic outcomes has become critical. Traditional assessment methods often fail to provide timely insights into students at risk. This study applies machine learning techniques to demographic, behavioral, and academic data to accurately classify student performance and aid in early intervention.

# Objectives
Identify key factors influencing academic performance

Train and evaluate machine learning models to classify students into performance categories

Provide actionable insights to educators and institutions for timely support

# Methodology
Dataset: Public student performance dataset sourced from Kaggle

# Preprocessing Techniques:

Feature encoding (label encoding)

Outlier detection and removal

Normalization using Z-score and Min-Max scaling

Exploratory Data Analysis (EDA)

Classification Models Used:

Random Forest (achieved best accuracy of 91.2%)

Support Vector Machine (SVM)

Gradient Boosting

Decision Tree

Gaussian Naïve Bayes (performed poorly due to strong independence assumptions)

# Workflow Summary
Data cleaning and normalization

Label encoding of categorical variables

Feature selection using correlation analysis and visualizations

Model training using various data splits (e.g., 80:20, 90:10)

Model evaluation using metrics such as accuracy, precision, recall, and F1-score

# Key Findings
Absenteeism had the highest negative correlation with GPA (-0.61)

Study time had a weak positive influence, while age showed negligible impact

Random Forest consistently outperformed other models across all evaluation metrics

Gaussian Naïve Bayes underperformed due to feature dependencies in the dataset
