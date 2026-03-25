# 🚀 AI-Based Loan Default Risk Prediction System

This project focuses on building an end-to-end Machine Learning system to predict whether a customer is likely to default on a loan using financial data.

---

## 🎯 Objective

The goal of this project is to help financial institutions identify high-risk borrowers and reduce financial losses by making accurate, data-driven lending decisions.

---

## 📊 Dataset Overview

- Type: Structured (Tabular Data)
- Problem Type: Binary Classification
- Target Variable: `Defaulted` (0 = No, 1 = Yes)
- Features:
  - Employment Status
  - Bank Balance
  - Annual Salary

⚠️ The dataset is **highly imbalanced**, with only ~3% of customers defaulting.

---

## 🧠 Machine Learning Workflow

### 1. Data Preprocessing
- Cleaned column names
- Removed unnecessary columns (Index)
- Handled missing values

### 2. Data Audit & Visualization
- Histograms for distribution analysis
- Boxplots for outlier detection
- Correlation heatmap for feature relationships

### 3. Outlier Handling
- Applied IQR (Interquartile Range) method to treat extreme values

### 4. Feature Engineering
- Created `debt_income_ratio` to capture financial risk behavior

### 5. Handling Imbalanced Data
- Applied **SMOTE (Synthetic Minority Over-sampling Technique)**

### 6. Model Training
Trained multiple machine learning models:
- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Gradient Boosting

### 7. Model Optimization
- Hyperparameter tuning using **GridSearchCV**
- Optimized classification threshold to maximize **Recall**

### 8. Model Evaluation
Used advanced evaluation metrics:
- Accuracy
- Precision
- Recall ⭐ (Most important)
- F1 Score
- ROC-AUC

### 9. Explainable AI (XAI)
- Used **SHAP (SHapley Additive Explanations)** to interpret model decisions

---

## 📈 Key Results

- Achieved high **Recall**, reducing false negatives (missed defaulters)
- Improved **F1-score** after hyperparameter tuning
- Identified important features influencing loan default
- Built a robust model suitable for financial risk prediction

---

## 💼 Business Impact

This system can help banks and fintech companies:
- Reduce loan default risk
- Improve approval decisions
- Save significant financial losses
- Automate risk assessment using AI

---

## 🧬 Sample Visualizations

### 🔹 Confusion Matrix


### 🔹 Precision-Recall Curve


### 🔹 SHAP Feature Importance


---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Imbalanced-learn (SMOTE)
- SHAP (Explainable AI)

---

---

## 🚀 Future Improvements

- Deploy as a web app using Streamlit
- Integrate real-time prediction system
- Use deep learning models for better performance
- Add more financial features for improved accuracy

---

## 👨‍💻 Author

- ANANTHARAJAN VEL MURUGAN
- AI & Machine Learning Student
- Open to Internship/job Opportunities 🚀

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and connect with me on LinkedIn!


