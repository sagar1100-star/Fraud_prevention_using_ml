# 🛡️ Fraud Prevention Using Machine Learning

This project is a machine learning pipeline for detecting fraudulent transactions using multiple ML models including XGBoost and stacked ensembles.

## 📂 Project Structure

- `fraud_stack.pkl`: Stacked model trained for fraud detection.
- `fraud_xg.pkl`: XGBoost model trained for high accuracy.
- `dataset.csv`: Cleaned and preprocessed transactional data.
- `predict.py`: Python script to make predictions using the trained models.
- `notebooks/`: Contains exploratory data analysis and model training steps.

## 🚀 Technologies Used

- Python
- Scikit-learn
- XGBoost
- Pandas, NumPy
- Matplotlib, Seaborn

## 🔍 How It Works

1. Load the pre-trained model.
2. Pass transactional data as input.
3. Get binary classification output (fraud or not fraud).

## 📈 Accuracy

✅ Achieved over **97% accuracy** on validation data using the stacked model.

## 📂 Example Usage

```python
import joblib
model = joblib.load('fraud_stack.pkl')
prediction = model.predict([input_features])
