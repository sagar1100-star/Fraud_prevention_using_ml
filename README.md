
---

## ✅ OPTION 2 — Extended Version (With Enhancements & Future Plans)

```markdown
# 🛡️ Fraud Prevention Using Machine Learning

This machine learning project focuses on detecting fraudulent financial transactions. It features a well-structured pipeline using two ML models (`XGBoost`, `Stacked Ensemble`) and includes ready-to-use `.pkl` files for deployment.

---

## 📁 Contents

- `fraud_stack.pkl` – Stacked model with high accuracy
- `fraud_xg.pkl` – XGBoost model for fraud classification
- `predict.py` – Prediction script using pre-trained models

---

## 🚀 How to Predict

```python
import joblib

model = joblib.load("fraud_stack.pkl")
input_data = [[1200.50, 1, 0, 300.0, 100.0, 0.75]]  # Replace with real input
prediction = model.predict(input_data)
print("Prediction:", prediction)
