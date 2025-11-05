# Credit Card Fraud Detection (Machine Learning)

This project focuses on detecting fraudulent credit card transactions using machine learning. The dataset used is the **Kaggle Credit Card Fraud Detection dataset**, which contains real transactions made by European cardholders in 2013.

The data is highly imbalanced, as fraudulent transactions represent only **0.17%** of the total records. To handle this, machine learning techniques were applied to classify transactions as legitimate or fraudulent.

---

## 📂 Project Files

| File | Description |
|------|--------------|
| `fraud_detection.ipynb` | Main Jupyter Notebook containing the analysis and ML models |
| `creditcard.csv` | Dataset used for training and testing |
| `fraud_model.pkl` | Saved trained ML model (Random Forest or Logistic Regression) |

---

## 🧠 Project Overview

### ✅ Steps Covered in the Notebook:

- Data loading & basic exploration  
- Data preprocessing and feature scaling  
- Train-test split  
- Machine Learning models used:  
  - Logistic Regression  
  - Random Forest Classifier  
- Model evaluation with accuracy score & classification report  
- Saved the best-performing model as `fraud_model.pkl`

---

## 🧪 Models Used

| Model | Purpose |
|--------|------------|
| Logistic Regression | Baseline model |
| Random Forest | Improved performance model |

---

## 📊 Evaluation Metrics

The following metrics were used to check model performance:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

> Note: Because the dataset is imbalanced, accuracy alone is not enough. Precision & Recall are more important for fraud detection.

---
⚠️ Disclaimer

This is a learning project for educational purposes only.
It should not be used as a real-world fraud detection system.
