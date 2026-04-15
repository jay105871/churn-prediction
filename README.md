# 📊 Customer Churn Prediction

## 📌 Overview
This project predicts customer churn for a telecom company using machine learning. The goal is to identify customers at risk of leaving and provide actionable insights to improve retention strategies.

---

## 🎯 Business Problem
Customer churn directly impacts revenue. By predicting which customers are likely to leave, businesses can proactively target retention efforts and reduce loss.

---

## 🧰 Tools & Technologies
- Python (Pandas, NumPy)
- Scikit-learn (Random Forest)
- Matplotlib & Seaborn
- Jupyter Notebook

---

## 📊 Dataset
- Telco Customer Churn Dataset
- Includes customer demographics, account details, and service usage

---

## 🧹 Data Preparation
- Removed unnecessary columns (customerID)
- Converted TotalCharges to numeric
- Handled missing values
- Applied one-hot encoding to categorical variables

---

## 🤖 Model
- Random Forest Classifier
- Train/Test Split: 80/20

---

## 📈 Results
- Model Accuracy: (ADD YOUR ACTUAL NUMBER)
- Evaluated using confusion matrix and classification report

---

## 📊 Key Insights
- Month-to-month contract customers have higher churn risk
- Higher monthly charges are associated with increased churn
- Longer tenure customers are less likely to churn

---

## 📁 Project Structure
churn-prediction/
│
├── data/
├── notebooks/
├── outputs/
├── scripts/
├── README.md
└── requirements.txt


---

## ⚠️ Limitations
- No time-series behavioral data
- Limited feature engineering
- Model not hyperparameter tuned

---

## 🚀 Future Improvements
- Try XGBoost / Logistic Regression
- Perform hyperparameter tuning
- Deploy model as an API

---

## 👤 Author
Jordan Chambers  
Data Analyst | Python | Machine Learning
