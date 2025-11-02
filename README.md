# 🎓 Predicting Student Depression Using Data-Driven Approaches for Preventive Mental Health Care

> **A Machine Learning–Driven Approach for Early Depression Risk Prediction Among Students**

---

## 📘 Overview

Student depression has become a serious global issue affecting academic performance, productivity, and well-being.  
This project leverages **machine learning techniques** to predict **depression risk levels** among students based on academic, behavioral, and lifestyle factors.

The goal is to shift mental healthcare from **reactive treatment** to **proactive prevention** through data-driven insights.

---

## 🧠 Objectives

- Identify **key predictors** of student depression using real-world data.  
- Develop a **supervised classification model** to classify students as *High-Risk* or *Low-Risk*.  
- Support **preventive mental healthcare** through predictive analytics aligned with **UN SDG 3 – Good Health and Well-Being**.

---

## 🗂️ Dataset

- **Source:** [Kaggle – Student Depression Dataset](https://www.kaggle.com/datasets/ngdihkhoi/student-depression-dataset)  
- **Samples:** 27,902 students  
- **Target Variable:** `Depression Risk` (1 = High, 0 = Low)  
- **Key Features:**  
  - Academic Pressure  
  - Sleep Duration  
  - Financial Stress  
  - Study Satisfaction  
  - Work/Study Hours  
  - Family Mental Health History  

---

## ⚙️ Methodology

This project follows a structured **data science pipeline**:

1. **Data Preprocessing**  
   - Handle missing values & data inconsistencies  
   - Encode categorical variables  
   - Detect and handle outliers  
   - Scale numerical features  

2. **Exploratory Data Analysis (EDA)**  
   - Analyze feature distributions & correlations  
   - Identify relationships between lifestyle factors and depression risk  

3. **Model Development**  
   - Algorithms used:  
     - Logistic Regression  
     - Support Vector Machine (SVM)  
     - Decision Tree  
     - Random Forest  
     - XGBoost  
   - Evaluation Metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC  

4. **Model Evaluation & Selection**  
   - Logistic Regression and SVM achieved the best generalization  
   - **Best Model ROC-AUC ≈ 0.886**  
   - Used `class_weight = 'balanced'` to handle class imbalance  

---

## 🔍 Key Findings

- **High academic pressure**, **long study/work hours**, and **financial stress** are the strongest predictors of depression.  
- **Reduced sleep (<7 hours)** and **low study satisfaction** further increase risk.  
- **High CGPA** and **study satisfaction** correlate with lower depression risk.  
- **SVM** and **Logistic Regression** provided the best trade-off between accuracy and interpretability.

---

## 🌍 Social Impact & SDG Alignment

This work aligns with **United Nations Sustainable Development Goal (SDG) 3** – *Good Health and Well-Being*.  
By applying AI in mental healthcare, the project promotes:

- Early detection and intervention  
- Scalable mental health monitoring  
- Data-driven awareness programs for student well-being  

---

## 🚀 Future Scope

- **Mobile Health Apps:** Personalized depression risk assessment and lifestyle guidance  
- **Clinical Decision Support Systems (CDSS):** For universities and counselors  
- **Public Health Integration:** Data-backed interventions addressing academic and financial stress  

---

## 🧩 Technologies Used

- **Python Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, LightGBM  
- **Environment:** Jupyter Notebook / Google Colab  
- **Dataset Source:** Kaggle  

---

## 🧑‍💻 Author

**Name:** H. K. I. Dhananjaya  
**University:** NSBM Green University  
**Student ID:** 27595  

> *“Data science isn’t just about numbers — it’s about uncovering insights that can improve lives.”* 💙  

---

## 🏷️ Keywords

`Machine Learning` · `Data Science` · `Mental Health` · `Predictive Analytics` · `Student Depression` · `Preventive Healthcare` · `AI for Good`

---
