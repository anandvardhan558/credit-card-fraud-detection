# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview
Credit card fraud detection is a critical problem due to the highly imbalanced nature of transaction data.  
This project applies **Machine Learning techniques** along with **sampling methods** to accurately identify fraudulent credit card transactions.

---

## 🎯 Objective
- Handle class imbalance in fraud data
- Compare multiple machine learning models
- Select the best-performing model for fraud detection

---

## 📊 Dataset Description
- Credit card transaction dataset
- Highly imbalanced (fraudulent transactions are very few)
- Features: `V1` to `V29` (PCA transformed)
- Target variable: `Class`  
  - `0` → Normal Transaction  
  - `1` → Fraudulent Transaction  

---

## ⚙️ Data Preprocessing
- Feature scaling using **StandardScaler**
- Separation of features and target variable
- Train-test split for model evaluation

---

## 🔁 Sampling Techniques Used
To handle class imbalance:
- **Under-Sampling**
- **Over-Sampling**

---

## 🤖 Machine Learning Models
Each sampling technique was tested using:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## 📈 Model Evaluation Metrics
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score

---

## 🏆 Best Model
After comparing all models:

✅ **Random Forest with Over-Sampling** achieved the best performance  
- High recall for fraud detection  
- Better handling of imbalanced data  

This model was selected as the **final model** and saved for prediction.

---

## 🚀 Final Outcome
- Improved fraud detection accuracy
- Reduced false negatives
- Reliable and scalable fraud detection system

---

## 🛠 Technologies Used
- Python
- NumPy, Pandas
- Scikit-learn
- Imbalanced-learn
- Joblib

---

## 📌 Conclusion
Handling class imbalance is crucial in fraud detection.  
**Over-Sampling combined with Random Forest** provides the most effective results for detecting fraudulent transactions.

---
Copyright © 2026 Anand Vardhan
