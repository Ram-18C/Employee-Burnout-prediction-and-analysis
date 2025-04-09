# 🔥 Employee Burnout Prediction & Analysis

This project aims to predict employee burnout using machine learning techniques. Built during my internship at **EDUNET Foundation**, it focuses on early identification of burnout risks to help HR teams take timely action.

## 🚀 Overview

Burnout in the workplace affects productivity, engagement, and employee well-being. This project uses employee data to build a machine learning model that accurately classifies whether an employee is at risk of burnout, based on key features such as workload, satisfaction, and work-life balance.

## 🧠 Machine Learning Approach

- **Model Used:** Random Forest Classifier  
- **Accuracy Achieved:** 85%
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score

## 📊 Features Used

Key features considered for the prediction model:
- Daily Work Hours
- Satisfaction Level
- Company Type
- Remote Work
- Mental Health History
- Work-Life Balance Rating
- Leave Taken

## ⚙️ Tech Stack

- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook / Google Colab  
- **Deployment:** Integrated with HR systems for real-time usage  

## 🛠️ Workflow

1. **Data Preprocessing:**
   - Handled missing values
   - Encoded categorical variables
   - Normalized numerical features

2. **Exploratory Data Analysis (EDA):**
   - Visualized distributions and correlations
   - Identified key burnout indicators

3. **Model Training & Testing:**
   - Trained Random Forest on training data
   - Tuned hyperparameters for better accuracy

4. **Evaluation:**
   - Achieved 85% accuracy on test set
   - Validated model with confusion matrix & ROC curve

5. **Integration:**
   - Final model was serialized using `joblib`
   - Deployed into an HR dashboard for practical use

## 📁 Folder Structure

