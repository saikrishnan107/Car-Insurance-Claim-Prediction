# Car Insurance Claim Prediction

## Problem Statement
Predict whether a policyholder will file a car insurance claim using demographic, vehicle, and policy features.

## Dataset
Source: Provided insurance dataset  
Target variable: is_claim

## Approach
- Exploratory Data Analysis
- Data Preprocessing
- Baseline Modeling
- Advanced Modeling
- Hyperparameter Tuning
- Model Evaluation

## Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- LightGBM

## Evaluation Metrics
Accuracy, Precision, Recall, F1 Score, ROC-AUC

## Final Model
LightGBM (Tuned)

## Results
Achieved highest ROC-AUC and F1-score using ensemble methods.

## Limitations
- Class imbalance 
- Limited behavioral features

## Solution for Imbalance
- SMOTE
- SHAP explainability
- Real-time deployment
