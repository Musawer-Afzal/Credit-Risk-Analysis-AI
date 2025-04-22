### 📁 3. **Credit Risk Analysis**

# 🏦 Credit Risk Analysis

This project predicts the likelihood of an individual defaulting on a loan using classification algorithms. It handles imbalanced data and evaluates models to determine credit risk.

## 🧠 Project Goals

- Handle missing data and perform feature engineering
- Use SMOTE for class imbalance
- Train a Random Forest classifier
- Tune threshold for best performance
- Predict on new data for risk classification

## 📦 Dataset

- Source: "Give Me Some Credit" dataset (Kaggle)
- Files: `cs-training.csv`, `cs-test.csv`, `sampleEntry.csv`

## 🛠️ Technologies

- Python (Pandas, NumPy)
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Matplotlib
- Joblib (for saving models)

## 📊 Features

- Binary classification (0: Not at risk, 1: At risk)
- Threshold tuning for better precision/recall
- Custom model saving/loading

## 📁 Files

- `credit_risk_model.py` – Full training and prediction script
- `submission.csv` – Final predictions for test data
- `README.md` – Project overview

## 🔍 Sample Output

- Confusion matrix and classification report
- Threshold-based predictions
- Submission CSV with predicted labels
