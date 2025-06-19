# 🛡️ Fraud Prevention Using Machine Learning

This project uses machine learning models like XGBoost and a stacked ensemble to detect fraudulent financial transactions. It includes pre-trained models and prediction scripts for real-time use.

## 📁 Project Contents

- `fraud_stack.pkl` – Stacked ensemble ML model.
- `fraud_xg.pkl` – XGBoost classifier.
- `predict.py` – Script to run predictions using trained models.
- `dataset.csv` – Dataset used for training (if available).
- Jupyter notebooks (optional): for training and evaluation.

## 🔍 Features

- Preprocessing and feature engineering
- Trained models using real-world fraud detection datasets
- Stacking and boosting techniques used
- Ready-to-use `.pkl` models
- 97%+ model accuracy achieved in validation

## 🧠 Technologies Used

- Python 3
- Scikit-learn
- XGBoost
- Pandas, NumPy
- Seaborn, Matplotlib

## ⚙️ How to Use

```python
import joblib

model = joblib.load("fraud_stack.pkl")
input_data = [[...]]  # Replace with real input
result = model.predict(input_data)
print("Prediction:", result)
