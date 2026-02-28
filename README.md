# 📊 Customer Churn Prediction using Machine Learning

## 🚀 Project Overview

Customer churn is a major challenge in the telecom industry. This project builds a predictive machine learning model to identify customers who are likely to churn. 

The project combines:
- Machine Learning (Logistic Regression)
- Explainable AI (SHAP)
- SQL-based aggregation
- Customer segmentation strategy

The final model achieved **~80% accuracy** in predicting customer churn.

---

## 🎯 Objectives

- Build a binary classification model for churn prediction
- Identify key churn drivers using SHAP explainability
- Perform SQL-based aggregation for business insights
- Segment customers into risk-based categories
- Provide actionable retention strategies

---

## 📂 Project Structure
Customer_Churn_Project/
│
├── Customer_Churn_Analysis.ipynb
├── Customer_Segmentation_Output.csv
├── Final_Customer_Churn_Report_2_Pages.pdf
├── Final_Customer_Churn_Presentation.pptx
└── README.md

---

## 🛠️ Tools & Technologies Used

- Python
- Pandas & NumPy
- Scikit-learn
- SHAP (Explainable AI)
- SQLite (SQL simulation)
- Matplotlib & Seaborn
- Jupyter Notebook

---

## 🔍 Methodology

### 1️⃣ Data Preprocessing
- Removed unnecessary columns
- Handled missing values
- One-hot encoding of categorical variables
- Feature scaling using StandardScaler

### 2️⃣ Model Development
- Train-test split (80%-20%)
- Logistic Regression model
- Evaluation using:
  - Accuracy
  - Confusion Matrix
  - Precision / Recall / F1-score

### 3️⃣ Explainability
- Used SHAP to identify key churn drivers:
  - Tenure Months
  - Total Charges
  - Contract Type
  - Internet Service

### 4️⃣ SQL Aggregation
Executed SQL queries to analyze:
- Churn by contract type
- Average charges by churn status
- Churn distribution across services

### 5️⃣ Customer Segmentation
Customers categorized into:
- 🔴 At Risk
- 🟡 Dormant
- 🟢 Loyal

---

## 📈 Results

- Model Accuracy: **~80%**
- Identified high-risk customers
- Extracted actionable churn drivers
- Built segmentation strategy for retention campaigns

---

## 💡 Business Insights

- Month-to-month contracts show higher churn.
- Customers with short tenure are more likely to leave.
- Fiber optic users have higher churn probability.
- Long-term contracts significantly reduce churn risk.

---

## 📊 Future Improvements

- Implement Random Forest / XGBoost
- Handle class imbalance using SMOTE
- Deploy model using Flask or Streamlit
- Create real-time churn dashboard

---

## 🧠 Author

**Ruchu Kurian**  
MCA Student | Aspiring Data Scientist  

---

## ⭐ If you found this project useful, feel free to star the repository!
