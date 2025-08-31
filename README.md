# AI-Powered Employee Attrition Prediction

## 📌 Project Overview
This project predicts whether an employee is likely to leave the company (attrition) using the **IBM HR Analytics Employee Attrition & Performance** dataset from Kaggle.  
It was built as part of an AI Intern technical task to demonstrate skills in:
- Data cleaning and preprocessing
- Model building and evaluation
- Visualization of key insights
- Clear documentation and communication

---

## 📂 Dataset
Source: [IBM HR Analytics Dataset - Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)  

The dataset contains employee demographic details, job-related attributes, and whether they left the company.

---

## 🛠 Tech Stack
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Scikit-learn** (for ML model training & evaluation)
- **Jupyter Notebook** (development environment)

---

## 📊 Steps Performed

### 1. Data Understanding & Preprocessing
- Loaded dataset and explored structure
- Handled missing values (if any)
- Encoded categorical variables
- Scaled/normalized numerical features
- Visualized relationships between key features and attrition

### 2. Model Building
- Chose  Random Forest
- Split data into **train (80%)** and **test (20%)**
- Performed basic hyperparameter tuning

### 3. Model Evaluation
- Metrics: Accuracy, Precision, Recall, F1 Score
- Confusion Matrix visualization
- Extra visualization: ROC Curve / Precision-Recall Curve
