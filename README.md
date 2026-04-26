📊 Customer Churn Prediction (Capstone Project)

🚀 End-to-End Machine Learning Capstone Project with Business Impact

---

🎓 Capstone Project Details

Customer churn is one of the biggest challenges in the telecom industry. Retaining existing customers is significantly more cost-effective than acquiring new ones.

This capstone project focuses on predicting customer churn using machine learning and uncovering key business insights to help reduce customer attrition.

---

## 🧠 Problem Statement

A telecom company (**AlphaCom**) is experiencing increasing customer churn, impacting revenue and customer retention. Traditional methods fail to identify churn proactively.

👉 The goal is to:

* Predict customers likely to churn
* Identify key factors influencing churn
* Provide actionable strategies for retention

---

## 🎯 Objectives

* Build predictive models to identify churn risk
* Perform Exploratory Data Analysis (EDA)
* Analyze customer behavior patterns
* Improve model performance using tuning
* Deliver business-driven recommendations

---

## 📂 Dataset Information

* 📊 Total Records: **12,055 customers**
* 📌 Features: **20 variables**
* 🎯 Target Variable: `Churn` (1 = Yes, 0 = No)

### Features Include:

* Demographics (Gender, Senior Citizen, Partner, Dependents)
* Services (Internet, Tech Support, Streaming, etc.)
* Billing (Monthly Charges, Payment Method)
* Customer tenure

---

## 🧹 Data Preprocessing

* Removed special characters from monetary values
* Converted `MonthlyCharges` & `TotalCharges` to numeric
* Handled missing values using **median imputation**
* Converted categorical variables using encoding
* Standardized target variable (`Churn`)

---

## 📊 Exploratory Data Analysis (EDA)

### 🔍 Univariate Analysis

* Majority of customers are **non-churners**
* Many customers have **low tenure**

### 🔗 Bivariate Analysis

* **Month-to-month contracts → Highest churn**
* **Low tenure customers → High churn risk**
* **Electronic check users → Higher churn**

### 🔥 Multivariate Insights

* Contract type + tenure + monthly charges strongly impact churn
* Customers with high charges and short tenure are most likely to churn

---

## 🤖 Machine Learning Models

### Baseline Model

* Logistic Regression

### Advanced Models

* Decision Tree
* Random Forest

### ⚙️ Model Improvement

* Hyperparameter tuning applied
* Performance improved after tuning

---

## 📈 Model Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score

---

## 🏆 Key Results

* Contract type is the **strongest predictor of churn**
* Customers with **short tenure are high-risk**
* **Automatic payment methods reduce churn**
* Tuned models performed better than baseline

---

## 💡 Business Insights

* Customers on **month-to-month plans churn more**
* Customers with **higher monthly charges are more likely to leave**
* Lack of **tech support & security services increases churn risk**

---

## 📢 Business Recommendations

* ✅ Promote long-term contracts (1-year / 2-year plans)
* 🎯 Target low-tenure customers with onboarding offers
* 💳 Encourage automatic payment methods
* 🛠 Improve customer support services
* 💰 Offer personalized discounts for high-value customers

---

## 🛠️ Tech Stack

* **Programming:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn
* **Visualization:** Matplotlib, Seaborn
* **Tools:** Jupyter Notebook

---


