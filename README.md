# 🔍 Fraud Detection using Machine Learning

This project focuses on building a fraud detection system using a highly imbalanced dataset of financial transactions. Various models including Logistic Regression, Random Forest, LightGBM, and XGBoost were trained and evaluated with performance metrics.

## 📌 Objective
To accurately identify fraudulent transactions while minimizing false positives in a class-imbalanced setting.

## 📂 Dataset
The dataset contains transaction records including:
- `step`, `type`, `amount`, `oldbalanceOrg`, `newbalanceOrig`, etc.

## ⚙️ Techniques Used
- Data Cleaning & EDA
- SMOTE for class imbalance
- Feature Selection & Importance
- Model Training: Logistic Regression, Random Forest, LightGBM, XGBoost
- Evaluation: Confusion Matrix, Classification Report, ROC/AUC

## 📈 Results
Best performing model: **XGBoost**
- Accuracy: ~99.9%
- Fraud Detection Recall: ~99%

## 💾 Tools
- Python, Pandas, Scikit-Learn, Imbalanced-learn, XGBoost, LightGBM
- Jupyter Notebook

## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook project fraud detection.ipynb
