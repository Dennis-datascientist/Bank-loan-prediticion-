# Bank Loan Prediction Model

## Overview
This project implements a deep learning model to predict bank loan approval using a Neural Network. The model uses various applicant features such as income, credit history, and personal information to predict loan approval status.

## Dataset
The project uses 'bankloan.csv' which contains the following features:
- Loan_ID
- Gender
- Married
- Dependents
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area
- Loan_Status

## Model Architecture
- Input Layer: 17 features (after one-hot encoding)
- Hidden Layer 1: 400 neurons (ReLU)
- Hidden Layer 2: 800 neurons (ReLU)
- Hidden Layer 3: 10 neurons (ReLU)
- Output Layer: 1 neuron (Sigmoid)

## Model Performance
- Training Accuracy: 92.09%
- Confusion Matrix Results:
  - True Negatives: 44
  - True Positives: 66
  - False Negatives: 21
  - False Positives: 2

## Dependencies
- pandas
- numpy
- scikit-learn
- imbalanced-learn (SMOTE)
- tensorflow
- seaborn
- matplotlib

## Files
- `bank.ipynb`: Jupyter notebook containing the model implementation
- `bankloan.csv`: Dataset file
