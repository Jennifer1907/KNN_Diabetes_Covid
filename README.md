# Diabetes Progression Prediction using KNN Regression

## Guidance from 
Hoàng-Nguyên Vũ (AI Vietnam)

## 📘 Project Description

### 📌 Background
Diabetes is a chronic disease affecting millions worldwide. Monitoring its progression through biological indicators helps doctors make early, accurate, and personalized treatment decisions.  
This project simulates the prediction of diabetes progression using patient clinical features and the **K-Nearest Neighbors (KNN) Regression** algorithm. The dataset used is a standardized medical dataset from the U.S. National Institutes of Health.

### 🎯 Objective
To build a regression model using **KNN Regression** to predict the diabetes progression index based on the following input features:

- Age  
- Gender  
- BMI (Body Mass Index)  
- Blood Pressure  
- Other biological indicators (e.g., cholesterol, glucose)

The output is a **continuous numerical value** representing the severity of the disease.

---

## 📊 Dataset

The project uses the `load_diabetes()` dataset from the **scikit-learn** library.

- **Instances:** 442 patients
- **Features:** 10 clinical indicators (standardized)
- **Target (`y`)**: A quantitative score representing diabetes progression

---

## 🧠 Why KNN Regression?

KNN Regression is:
- Simple to implement  
- Requires no complex model training  
- Effective for small to medium datasets  
- A good baseline model in medical ML tasks


