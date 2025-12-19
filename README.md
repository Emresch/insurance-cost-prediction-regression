# 🏥 Insurance Cost Prediction with Linear Regression

This project applies **Machine Learning (Linear Regression)** to predict individual medical insurance costs based on personal attributes (age, BMI, smoking status, etc.).

## 📊 Project Overview
* **Goal:** Predict the `charges` (insurance cost) based on independent variables.
* **Model:** Linear Regression (Scikit-Learn).
* **Performance:** The model explains approx. **78%** of the variance in costs.

## 📂 Dataset Features
The dataset consists of the following parameters:
* **Age:** Age of the primary beneficiary.
* **Sex:** Gender (female/male).
* **BMI:** Body mass index.
* **Children:** Number of children covered by health insurance.
* **Smoker:** Smoking status (yes/no) - *High correlation with charges.*
* **Region:** Residential area in the US.

## 🛠️ Technologies Used
* **Python 3.x**
* **Pandas & NumPy** (Data Manipulation)
* **Scikit-Learn** (Model Training & Evaluation)
* **Matplotlib & Seaborn** (Visualization)

## 📈 Results
The model was evaluated using standard regression metrics:

| Metric | Score | Meaning |
|os|os|os|
| **R² Score** | **0.7836** | Strong relationship between features and cost. |
| **MAE** | **$4181.19** | Average absolute error in prediction. |
| **RMSE** | **$5796.28** | Root Mean Squared Error. |

