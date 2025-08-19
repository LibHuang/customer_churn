# Telecom Customer Churn Prediction

## Overview
This project predicts **customer churn** in the telecom industry using machine learning.  
By analyzing a telecom churn dataset, it identifies key drivers of churn and applies multiple classification models to evaluate predictive performance.  

The goal is to help telecom providers **flag high-risk customers early** and design **targeted retention strategies** to reduce revenue loss.  

---

## Project Structure


Project Structure
```text
Telecom.ipynb        # Main Jupyter notebook
Telco-Customer-Churn_revised.csv   # Dataset
README.md            # Project overview
```

---

## ⚙️ Steps Performed
1. **Data Loading & Exploration**
   - Imported churn dataset
   - Reviewed dataset size and structure
   - Explored churn distribution and customer demographics

2. **Data Visualization**
   - Histograms comparing churn vs. non-churn groups:
     - Monthly Charges
     - Total Charges
     - Streaming / Internet services  

3. **Modeling**
   - Implemented multiple ML models:
     - Logistic Regression  
     - K-Nearest Neighbors (KNN)  
     - Decision Tree  
     - Support Vector Machine (SVM)  
     - Ensemble models (Random Forest, Bagging, AdaBoost)  
     - Boosting models (XGBoost, LightGBM, CatBoost)  

4. **Model Evaluation**
   - Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC  
   - Generated ROC curves for best-performing models  

---

## 📊 Results & Findings
- **Top Models**  
  - Boosting algorithms (**XGBoost, LightGBM, CatBoost**) achieved the **highest ROC-AUC scores**.  
  - Random Forest also performed strongly compared to baseline models.  

- **Key Features**  
  - **Monthly Charges** and **Total Charges** were the most predictive.  
  - Customers with **higher monthly charges** and **shorter tenure** were more likely to churn.  
  - Service-related features (e.g., streaming, internet plans) influenced churn.  

- **Business Insights**  
  - High-risk customers can be proactively identified.  
  - Implementing **retention offers** (discounts, loyalty programs, or plan adjustments) could reduce churn and protect recurring revenue.  

---

#### Tools & Libraries
##### Tech Stack Used
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) 
![SQL](https://img.shields.io/badge/SQL-336791?style=flat&logo=postgresql&logoColor=white) 
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4EABCF?style=flat&logo=seaborn&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EE4C2C?style=flat&logo=xgboost&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-00B386?style=flat&logo=lightgbm&logoColor=white)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=flat&logo=catboost&logoColor=black)
