# Anemia Detection Using Machine Learning
**Overview**

This project develops a machine learning model to detect anemia using routine blood test parameters. It aims to assist in early diagnosis by providing a fast and reliable prediction system.

**Objectives**

Develop a predictive model for anemia detection
Analyze the impact of different blood parameters
Compare model performance with and without hemoglobin (Hb)
Ensure high accuracy and reliability for early screening

**Dataset Description**

The dataset is sourced from Mendeley Data and includes clinical and hematological parameters from pediatric anemia patients. It is designed to support the development of predictive models, aiding in early diagnosis and personalized management of anemia.

It contains key blood parameters commonly used in anemia diagnosis:

Hemoglobin (Hb)
Red Blood Cell Count (RBC)
Packed Cell Volume (PCV)
Mean Corpuscular Volume (MCV)
Mean Corpuscular Hemoglobin (MCH)
Mean Corpuscular Hemoglobin Concentration (MCHC)

The dataset is particularly useful for research in hematology, pediatric care, and healthcare prediction modeling, with labeled instances indicating whether a patient is anemic or not.

**Methodology**

Data Preprocessing
Handling missing values using mean imputation
Feature scaling and normalization
Model Development
Training using Logistic Regression
Experimentation
Model trained with all features
Model trained without hemoglobin (Hb)
Evaluation
Accuracy
ROC-AUC Score
False Positives & False Negatives

**Tech Stack**

Programming Language: Python
Libraries: Scikit-learn, Pandas, NumPy
Visualization: Matplotlib, Seaborn
Environment: Google Colab

**Project Analysis**

Predicts whether a person is anemic based on blood test parameters
Performs an ablation study by evaluating models with and without hemoglobin (Hb)
Analyzes the impact of individual features on model performance
Provides insights into feature importance for anemia detection
