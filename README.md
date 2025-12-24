# Parkinson’s Disease Classification (ML)

## Overview
Built and evaluated machine learning models to classify Parkinson’s disease using a high-dimensional dataset.

## Key Results
- Random Forest: Recall (Class 1) = 0.97, Accuracy = 0.82  
- XGBoost: ROC–AUC = 0.80 (Validation)

## Methods
- Preprocessing: scaling, duplicate removal
- Feature Selection: SelectKBest (chi-square)
- Imbalance Handling: Random Oversampling / SMOTE
- Models: Logistic Regression, SVM, Random Forest, XGBoost
- Evaluation: Confusion matrix, ROC curve, ROC–AUC, precision/recall/F1

## Tech Stack
Python, pandas, NumPy, scikit-learn, imbalanced-learn, matplotlib, xgboost

##Visualizations

### Class Distribution
![Class Distribution](images/ClassDistribution_pie-chart.png)


![Class Distribution](images/ClassDistribution_bar-chart.png)

##Model Evaluation

### Random Forest Confusion Matrix

![Confusion Matrix](images/Model_Performance_ConfusionMatrix-XGB.png)

![Confusion Matrix](images/Model_Performance_ConfusionMatrix-RF.png)

## ROC Curve (Random Forest vs XGBoost)

![ROC Curve](images/ROC-Comparision_RF_Vs_XGB.png)

