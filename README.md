**Heart Disease Prediction using Machine Learning (CRISP-DM)**

This repository contains an end-to-end educational Machine Learning project focused on predicting heart disease using clinical patient data.
The project follows the CRISP-DM (Cross-Industry Standard Process for Data Mining) methodology to ensure a structured, reproducible, and industry-aligned workflow.

**Project Objective**

The main goal is to support early detection of heart disease by building and comparing multiple supervised classification models.
This project emphasizes:
Reducing false negatives (undiagnosed patients)
Model performance comparison
Interpretability and evaluation in a healthcare context

**CRISP-DM Methodology Applied**

1.  **Business Understanding:**

Defined a healthcare decision-support problem, 

Translated business needs into a binary classification task (healthy vs. diseased patients)

2. **Data Understanding:**

Explored a medical dataset containing clinical, biological, and demographic features, 

Analyzed data distribution, missing values, and class imbalance

3. **Data Preparation**

Cleaned and standardized raw data

Handled missing and inconsistent values

Applied feature engineering (medical ratios, interaction features, age groups)

Encoded categorical variables and scaled numerical features

Addressed class imbalance using SMOTE

Built reusable preprocessing pipelines

5. **Modeling**

Implemented and compared multiple Machine Learning models:

Logistic Regression (SGD)

K-Nearest Neighbors (KNN)

Decision Tree (CART)

Random Forest

Support Vector Machine (SVM)

XGBoost

Hyperparameter tuning and cross-validation were used to improve model generalization.

6. **Evaluation**

Models were evaluated using:

Accuracy

Precision

Recall (Sensitivity)

F1-Score

ROC-AUC

Confusion Matrix

ROC and Precision-Recall curves

XGBoost achieved the best overall performance.

7. **Deployment (Conceptual)**

The final model and pipeline are structured to support future deployment (API or dashboard) for healthcare decision-makers.


**Technologies Used**

Python

Pandas, NumPy

Scikit-learn

Imbalanced-learn (SMOTE)

XGBoost

Matplotlib, Seaborn

**Key Learning Outcomes**

End-to-end Machine Learning workflow implementation

Application of CRISP-DM in a real-world healthcare scenario

Model comparison, evaluation, and interpretability

Handling imbalanced datasets in medical classification problems
