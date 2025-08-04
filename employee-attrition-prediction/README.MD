# 🧠 Employee Attrition Prediction Project

## 📌 Problem Statement

Employee attrition, or turnover, is a critical issue faced by companies. In this project, we analyze factors contributing to employee attrition using data from IBM HR Analytics. The goal is to uncover patterns through **Exploratory Data Analysis (EDA)** and train machine learning models to **predict whether an employee is likely to leave** the organization.

---

## 👩‍💻 Developed By

**Sumayya Fazal Hussain**  
Frontend Developer | AI Enthusiast | Medical Student  
Karachi, Pakistan 🌍  
_Governor Sindh GenAI Program_

---

## 📊 Dataset

- **Source**: [IBM HR Analytics Attrition Dataset - Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- **Target Column**: `Attrition` (Yes/No)
- **Features**: Age, Department, DistanceFromHome, Gender, MonthlyIncome, JobSatisfaction, OverTime, etc.

---

## 🔍 Part 1: Exploratory Data Analysis (EDA)

Answering key business questions:
- Total employees vs. those who left
- Average age of leavers vs. non-leavers
- Attrition by department
- Correlation: Distance from home vs attrition
- Impact of overtime on attrition
- Monthly income trends
- Missing values analysis

---

## 📈 Part 2: Visualizations

Visuals used:
- **Bar Chart**: Attrition Count
- **Boxplot**: MonthlyIncome vs. Attrition
- **Histogram**: Age by Attrition
- **Stacked Bar**: Department vs Attrition
- **Countplot**: JobSatisfaction vs Attrition
- **Heatmap**: Feature Correlations

---

## 🤖 Part 3: Machine Learning Models

### Preprocessing
- Encoding categorical variables using `LabelEncoder`
- Train/Test split (80/20)

### Models Trained
- **Logistic Regression**
- **Random Forest Classifier**

### Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Classification Report
- ROC Curve & AUC Score

---

## 🧪 Results

- Models successfully trained on encoded HR dataset.
- Random Forest generally outperforms Logistic Regression in accuracy and AUC.
- Overtime, JobSatisfaction, and MonthlyIncome show high influence on attrition.

---

## ✅ Final Output

This notebook includes:
- ✅ Complete EDA with business insights
- ✅ All required visualizations
- ✅ ML model training and evaluation
- ✅ ROC curve and predictions

---

## 📁 How to Run

1. Install requirements:  
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
