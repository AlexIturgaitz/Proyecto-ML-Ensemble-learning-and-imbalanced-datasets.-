# Proyecto-ML-Ensemble-learning-and-imbalanced-datasets.-
Proyecto Machine Learning Avanzado, entrega D1

# Dry Bean Classification Project

## Overview
This project focuses on the classification of dry bean types using machine learning techniques. It includes data preprocessing, imbalance handling, model comparison, and hyperparameter tuning.

## Dataset

The dataset used in this project is publicly available at:

https://drive.google.com/drive/folders/1o2cD3uT8fYy5wLHHSwbfsxDJD6MzkGzK?usp=drive_link

The folder contains:
- `Dry_Bean_Dataset.xlsx` - original dataset  
- `train_data_SMOTE.csv` - balanced training set  
- `train_data_IMBALANCED.csv` - original training set  
- `test_data_FINAL.csv` - final test set  

## Project Structure

- `main.ipynb` - main notebook with full analysis and models  
- `README.md` - project description  
- Dataset files - available via Google Drive  

## Methodology

The project follows these main steps:

1. **Preprocessing**
   - Encoding categorical variables
   - Train/test split (80/20, stratified)
   - Missing data handling (SimpleImputer)
   - Feature scaling (StandardScaler)

2. **Imbalance Handling**
   - Random Undersampling
   - Random Oversampling
   - SMOTE (used for training)

3. **Modeling**
   - Baseline models (Logistic Regression, Decision Tree)
   - Ensemble methods (Random Forest, Gradient Boosting, AdaBoost, XGBoost)

4. **Hyperparameter Tuning**
   - Optuna with cross-validation
   - MedianPruner for XGBoost

5. **Evaluation**
   - Metrics: Accuracy, Precision, Recall, Macro F1, MCC
   - Final comparison on an untouched test set
   

## Reproducibility

All experiments can be reproduced using the provided datasets and the notebook.


## Requirements

Main libraries used:
- pandas
- numpy
- scikit-learn
- imbalanced-learn
- xgboost
- optuna
- matplotlib
- seaborn


## Authors

- Alvaro Franco, Cesar Llata, Alex Iturgaitz
- Group 17