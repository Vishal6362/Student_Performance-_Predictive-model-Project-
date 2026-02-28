# 🎓 Student Performance Predictive Model

## 📌 Project Overview
This project aims to build a Machine Learning model to predict whether a student will **Pass or Fail** based on academic performance and demographic factors.

The model helps identify key drivers that influence student success and provides insights for improving academic outcomes.

---

## 🎯 Objective
To analyze student data and develop a predictive classification model that determines student performance using features such as study hours, attendance, and previous scores.

---

## 📊 Dataset Information

The dataset contains **100 student records** with the following features:

- Student_ID  
- Gender  
- Study_Hours  
- Attendance  
- Previous_Score  
- Parental_Education  
- Internet_Access  
- Extracurricular  
- Final_Score  
- Result (Target Variable: Pass/Fail)

---

## 🛠 Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook  

---

## ⚙️ Project Workflow

1. Data Loading and Inspection  
2. Handling Missing Values  
3. Encoding Categorical Variables  
4. Feature Selection  
5. Train-Test Split (80% Train / 20% Test)  
6. Model Training using Logistic Regression  
7. Model Evaluation:
   - Accuracy Score  
   - Confusion Matrix  
   - Classification Report  
8. Feature Importance Visualization  

---

## 🤖 Machine Learning Model

Model Used: **Logistic Regression**

Reason for Selection:
- Suitable for binary classification
- Easy to interpret
- Provides feature importance insights

---

## 📈 Model Performance

The model achieved strong accuracy on the test dataset.

Key influential features:
- Study Hours  
- Attendance  
- Previous Score  
- Final Score  

---

## 🔍 Key Insights

- Higher study hours significantly increase the probability of passing.
- Attendance plays a crucial role in academic performance.
- Previous academic performance strongly impacts final outcomes.
- Access to internet and extracurricular activities show moderate influence.

---

## 📌 Conclusion

The predictive model successfully classifies student outcomes and highlights the most important factors affecting academic success.

This project demonstrates practical skills in:
- Data Cleaning  
- Exploratory Data Analysis  
- Feature Engineering  
- Machine Learning Modeling  
- Model Evaluation  
- Data Visualization  

---

## 🚀 How to Run the Project

1. Clone the repository
2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib scikit-learn
