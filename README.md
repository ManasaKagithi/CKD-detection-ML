# CKD-detection-ML
ML-based Chronic Kidney Disease classification with novel feature engineering


# Chronic Kidney Disease Detection using Machine Learning

## Objective
To build a machine learning model for classifying Chronic Kidney Disease (CKD) with high accuracy and introduce a novel biological feature for enhanced performance.

## Dataset
- 400 records × 26 features (clinical + lab data)
- Publicly available CKD dataset

## Tools & Tech
- Python
- Jupyter Notebook
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib
- Model: Random Forest Classifier

## Unique Feature: Renal Burden Index (RBI)
A newly engineered feature that quantifies kidney toxicity.

```formula used
RBI = (Blood Urea + Serum Creatinine + Blood Glucose) / (Hemoglobin × Specific Gravity)
