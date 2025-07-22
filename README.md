# CodeAlpha_DiseasePrediction

This project predicts the risk of heart or stroke disease using machine learning techniques as part of the CodeAlpha internship.

## Dataset

- Dataset: Framingham Heart Study
- File: heart_disease.csv

## Tools Used

- Python
- Pandas, NumPy
- Scikit-learn
- imbalanced-learn (SMOTE)
- Random Forest Classifier

## Process

- Data cleaning
- Encoding categorical values
- Feature scaling
- Train/test split
- SMOTE for class imbalance
- Model training and evaluation

## Results

### Before SMOTE
- Accuracy: 83.8%
- Recall (Positive class): 0.07
- F1-Score: 0.11

### After SMOTE
- Accuracy: 78.6%
- Recall (Positive class): 0.22
- F1-Score: 0.26

## Files

- Disease_Prediction_Model.ipynb
- heart_disease.csv
