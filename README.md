# Diabetes Prediction Model 🩺

This project uses Machine Learning to predict diabetes in patients based on medical metrics like Glucose levels, BMI, and Age.

## 📊 Dataset Overview
The dataset contains 768 records of female patients. Key features include:
* **Glucose**: Plasma glucose concentration.
* **BMI**: Body Mass Index.
* **Age**: Age of the patient.
* **Outcome**: 0 (Non-diabetic), 1 (Diabetic).

## 🛠️ Methodology
1. **Data Scaling**: Used `StandardScaler` to normalize the input data.
2. **Model Training**: Implemented **Support Vector Machine (SVM)** and **Decision Tree Classifier**.
3. **Optimization**: Iterated through 100 random states to find the most accurate Decision Tree model.
4. **Evaluation**: Used ROC Curves and AUC scores to measure diagnostic performance.

## 📈 Results
The model successfully identifies key risk factors, with Glucose and BMI being the strongest predictors.
