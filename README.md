# Loan Approval Prediction using Machine Learning

## 📌 Overview
This project implements an end-to-end **Machine Learning pipeline** to predict loan approval outcomes based on applicant financial and demographic data. The goal is to demonstrate practical skills in **data preprocessing, exploratory data analysis (EDA), feature engineering, model building, and evaluation** using real-world structured data.

The project addresses a common **financial risk assessment problem**, where accurate predictions help minimize incorrect loan approvals and support data-driven decision-making.

---

## 📁 Dataset Description
The dataset contains historical loan application records, where each row represents an individual applicant and each column represents an attribute influencing loan approval.

### Features
**Numerical Features**
- Applicant Income  
- Co-Applicant Income  
- Loan Amount  
- Loan Amount Term  
- Credit History  

**Categorical Features**
- Gender  
- Marital Status  
- Education  
- Self-Employed  
- Property Area  

**Target Variable**
- `Loan_Status`
  - `1` → Loan Approved  
  - `0` → Loan Not Approved  

The dataset includes missing values, categorical variables, and features on different scales, making it suitable for demonstrating real-world data preprocessing techniques.

---

## 🔍 Exploratory Data Analysis (EDA)
EDA was performed to:
- Understand data distribution and feature relationships  
- Identify missing values and outliers  
- Analyze correlations between numerical features  

Visualizations such as histograms and correlation heatmaps were used to extract insights.

---

## ⚙️ Data Preprocessing & Feature Engineering
The following steps were applied:
- Handling missing values using appropriate imputation strategies  
- Encoding categorical variables using Label Encoding and One-Hot Encoding  
- Feature scaling using StandardScaler  
- Feature engineering to improve model performance  

---

## 🤖 Model Building
Multiple supervised classification models were trained and evaluated:
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Naive Bayes  

The dataset was split into training and testing sets using an **80–20 split**.

---

## 📊 Model Evaluation
Models were evaluated using standard classification metrics:
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

### Performance Comparison
- **Before Feature Engineering:** Naive Bayes showed the highest precision  
- **After Feature Engineering:** Logistic Regression achieved the best overall performance with improved accuracy, recall, and F1-score  

Model selection was based on **business-relevant metrics**, not accuracy alone.

---

## 🏆 Key Insights
- Feature engineering significantly improves model performance  
- Logistic Regression benefits the most from engineered features  
- Precision is a critical metric for financial risk assessment to minimize false loan approvals  
- Simpler models can perform competitively on well-structured data  

---

## 🚀 Future Improvements
- Hyperparameter tuning for model optimization  
- Cross-validation for more robust evaluation  
- Implementation of ensemble models (Random Forest, XGBoost)  
- Deployment using Streamlit or Flask  

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 👤 Author
**Kabir Patil**  
Aspiring Data Analyst / Data Scientist  

---

## 📄 License
This project is for educational and portfolio purposes.
