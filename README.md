This project focuses on understanding the clinical and statistical factors that contribute to heart disease by performing a detailed Exploratory Data Analysis (EDA) on the widely used Heart Attack dataset.
The goal is to discover meaningful insights, identify strong predictors, and prepare the foundation for building accurate machine-learning models for cardiovascular risk prediction.

🚀 Project Overview

Heart disease remains one of the leading causes of death globally. Early detection is essential—and data-driven insights can play a major role in timely risk assessment. This project analyzes 303 patient records across 14 medical attributes, including age, cholesterol levels, blood pressure, ECG findings, chest pain types, exercise-induced angina, and more.

Through comprehensive EDA, this project reveals:

Key trends and risk patterns

Relationships between clinical variables

Significant predictors of heart disease

Distribution patterns of both numerical and categorical features

Medical interpretations supported by data

The analysis is designed to support clinicians, researchers, and data scientists interested in understanding cardiovascular risk factors and building predictive healthcare models.


📊 Key Features of the Analysis

✔️ Data Cleaning & Quality Checks

Shape and structure overview

Missing values inspection

Data types and consistency checks

✔️ Descriptive Statistics

Detailed summary statistics

Distribution visualization for all major variables

✔️ Categorical Feature Exploration

Chest pain type, ECG results, thalassemia, angina

Class separation between diseased vs non-diseased patients

✔️ Numerical Feature Exploration

Resting blood pressure, cholesterol, oldpeak, thalach

Boxplots, histograms, KDE plots, and outlier inspection

✔️ Correlation & Risk Indicators

Correlation matrix

Heatmaps and pairwise relationships

Analysis of top predictors


🧠 Key Findings

Chest pain type, thalassemia, and the number of major vessels are among the strongest predictors of heart disease.

Patients with heart disease typically show higher oldpeak, lower thalach, and more frequent abnormal ECG results.

Numerical and categorical features combine effectively for predictive modeling.

The dataset is clean, balanced enough, and ready for machine learning tasks such as logistic regression, SVM, random forest, or XGBoost.

🗂️ Dataset Description

The dataset contains the following 14 attributes:

Age

Sex

Chest Pain Type (cp)

Resting Blood Pressure (trestbps)

Cholesterol (chol)

Fasting Blood Sugar (fbs)

Resting ECG Results (restecg)

Maximum Heart Rate Achieved (thalach)

Exercise-induced Angina (exang)

ST Depression (oldpeak)

Slope of ST Segment (slope)

Number of Major Vessels (ca)

Thalassemia (thal)

Target (1 = heart disease, 0 = no heart disease)

🎯 Goal of This Project
To uncover clinical insights and build a strong analytical foundation that supports machine-learning models aimed at heart disease prediction.
This analysis enables stakeholders to better understand cardiovascular risk patterns through data.

📌 Future Work

Feature engineering & scaling

Machine learning model development

Hyperparameter tuning

SHAP feature-importance interpretation

Deployment as a web or mobile prediction tool

🤝 Contribution
Contributions, improvements, and suggestions are welcome. Feel free to submit issues or pull requests.
✔️ Clinical Interpretation

Each pattern is analyzed from both a data science perspective and a medical standpoint, turning raw data into actionable insight.
