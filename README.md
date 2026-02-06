# Credit Card Fraud Detection using Machine Learning

## Project Overview
With the rapid growth of online transactions, credit card fraud has become a serious problem.  
The main goal of this project is to use machine learning techniques to identify fraudulent credit card transactions, especially when the dataset is highly imbalanced.

---

## Objective
The objectives of this project are:
- To handle the class imbalance between normal and fraudulent transactions  
- To compare different machine learning models  
- To select the best performing model for fraud detection  

---

## Dataset Description
This project uses a credit card transaction dataset.

- The dataset is highly imbalanced (fraud cases are very few)
- Features are named `V1` to `V29`, which are PCA transformed
- Target column: `Class`
  - `0` → Normal Transaction  
  - `1` → Fraudulent Transaction  

---

## Data Preprocessing
Before training the models, the following preprocessing steps were applied:
- Feature scaling using StandardScaler  
- Separation of features and target variable  
- Splitting the dataset into training and testing sets  

---

## Sampling Techniques
To deal with class imbalance, the following sampling techniques were used:
- Under-Sampling  
- Over-Sampling  

---

## Machine Learning Models Used
The following models were trained using each sampling technique:
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  

This helped in comparing the performance of different models.

---

## Model Evaluation Metrics
The models were evaluated using:
- Accuracy  
- Precision  
- Recall  
- F1-Score  

In fraud detection, recall is a very important metric because missing a fraud transaction can lead to financial loss.

---

## Best Model
After comparing all the models, it was observed that:

**Random Forest Classifier with Over-Sampling** performed the best.
- It detected fraudulent transactions more effectively  
- It reduced false negatives  
- It handled the imbalanced data better  

This model was selected as the final model and saved for future predictions.

---

## Final Outcome
- Improved fraud detection performance  
- Reduced chances of missing fraudulent transactions  
- A more reliable and practical fraud detection system  

---

## Technologies Used
- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Imbalanced-learn  
- Joblib  

---

## Conclusion
This project shows that handling class imbalance is crucial in credit card fraud detection.  
Using Over-Sampling along with a Random Forest Classifier gives better results compared to other models.

---

Copyright © 2026 Anand Vardhan
