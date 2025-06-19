# 🛡️ Fraud Prevention Using Machine Learning

This project is focused on detecting fraudulent transactions using machine learning algorithms. It includes pre-trained models (`.pkl`) and prediction logic, making it suitable for integration into real-world fraud detection systems.

---

## 📁 Project Contents

- `fraud_stack.pkl` – A stacked ensemble model trained for high accuracy.
- `fraud_xg.pkl` – An XGBoost model known for speed and performance.
- `predict.py` – Python script to load models and predict fraud status.
- `dataset.csv` (optional) – Cleaned dataset used for training.

---

## 🔍 Features

- Machine learning pipeline for fraud detection
- Ensemble model with stacking and boosting
- Achieves **97%+ accuracy**
- Real-time prediction script included
- Clean, modular code

---

## ⚙️ How to Run Predictions

```python
import joblib

# Load the stacked model
model = joblib.load("fraud_stack.pkl")

# Sample input (replace with real feature values)
input_data = [[...]]  

# Predict
prediction = model.predict(input_data)
print("Prediction:", prediction)
