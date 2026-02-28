# Telecommunication Churn Prediction using Machine Learning

## 📌 Project Overview
This project develops machine learning models to predict customer churn in a telecommunications company. The goal is to identify customers likely to discontinue services and support data-driven retention strategies.

## 📊 Dataset
- **Name:** Telco Customer Churn Dataset  
- **Source:** IBM Sample Data  
- **Size:** 7,043 customers, 20 features  
- **Target:** Churn (Yes/No)

## ⚙️ Methods
The project includes:

- Data cleaning and preprocessing  
- Handling missing values and class imbalance (SMOTE)  
- Exploratory Data Analysis (EDA)  
- Feature encoding (Label Encoding & One-Hot Encoding)  
- Model training and evaluation  

### Models Implemented
- Decision Tree  
- Random Forest  
- XGBoost  
- Logistic Regression  
- Support Vector Machine (SVM)

## 📈 Results
- Best accuracy: ~78–84% depending on model and preprocessing  
- Random Forest and XGBoost achieved strong performance  
- SMOTE improved minority class recall  

## 🧪 Reproducibility
To reproduce the results:

```bash
pip install -r requirements.txt
python train.py
