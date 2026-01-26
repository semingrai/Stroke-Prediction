# Stroke Prediction Using Machine Learning

## Overview
Machine learning model to predict stroke risk based on patient health metrics. Achieved 94% accuracy using Random Forest classifier.

## Dataset
- Source: Kaggle Stroke Prediction Dataset
- 5,110 patient records with 11 clinical features
- Target: Stroke occurrence

## Features
- Age, gender, hypertension, heart disease
- Average glucose level, BMI
- Smoking status, work type, residence type

## Methods
- Data cleaning: Handled missing BMI values using median imputation, encoding for categorical variables
- Models tested: Logistic Regression, Decision Tree, Random Forest
- Best model: Random Forest with 94% accuracy

## Results
- **RandomForest Accuracy:** 94%

## Technologies
- Python 3.14
- Pandas, NumPy, Scikit-learn
- Matplotlib, Seaborn

## Installation
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Usage
```bash
jupyter notebook stroke-prediction.ipynb
```

semingrai
