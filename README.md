### Heart-Disease-Detection-ML-Project
# Project Overview
This project predicts whether a patient has heart disease using the Heart Disease Dataset.
It uses Logistic Regression as a baseline machine learning model with proper data preprocessing, training, and evaluation techniques.

The goal is to build a simple and interpretable model that can assist in early detection of heart disease based on patient health attributes.

# Project Structure
Heart-Disease-ML
├── heart.csv
├── Heart_Disease_Project.ipynb
├── Heart_Disease_Project.html
├── Heart_Disease_Project_Report.docx
└── README.md

# Dataset Information
The dataset contains several medical attributes used to predict heart disease.
Common features include:
age – Age of the patient
sex – Gender (1 = male, 0 = female)
cp – Chest pain type
trestbps – Resting blood pressure
chol – Serum cholesterol
fbs – Fasting blood sugar
restecg – Resting electrocardiographic results
thalach – Maximum heart rate achieved
exang – Exercise induced angina
oldpeak – ST depression induced by exercise
slope – Slope of peak exercise ST segment
ca – Number of major vessels
thal – Thalassemia
target – Presence of heart disease (0 = No, 1 = Yes)

# Results
Test Accuracy: ~85%
Confusion Matrix: Displayed in notebook
Key Takeaway: Logistic Regression performs well as a baseline model for predicting heart disease and provides interpretable results.

# Requirements
Python 3.8+
Required libraries:
pandas / numpy / matplotlib / seaborn / scikit-learn 
Install dependencies:
# pip install pandas numpy matplotlib seaborn scikit-learn
