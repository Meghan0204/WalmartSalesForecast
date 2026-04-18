# 📊 Walmart Sales Forecasting – Data Analyst Portfolio Project

## 📌 Project Overview

This project analyzes historical retail sales data from Walmart stores to identify trends and build predictive models for weekly sales forecasting. The goal is to demonstrate skills in data cleaning, exploratory data analysis, feature engineering, and machine learning modeling.

---

## 🎯 Objectives

* Merge and clean multiple real-world datasets
* Perform exploratory data analysis (EDA) on sales trends
* Engineer time-based and economic features
* Build predictive models for weekly sales
* Compare model performance
* Extract business insights from the results

---

## 📂 Dataset Description

This project uses a Walmart retail dataset consisting of three files:

* **train.csv** – Historical weekly sales data by store and department
* **features.csv** – External factors such as temperature, fuel price, CPI, and unemployment
* **stores.csv** – Store type and size information

These datasets are merged to create a unified analytical dataset.

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## 🔍 Methodology

### 1. Data Preparation

* Loaded and merged three datasets on Store and Date
* Handled missing values
* Converted date features into usable time components

### 2. Feature Engineering

Created additional features such as:

* Year
* Month
* Week number
* Store and department identifiers
* Economic indicators (CPI, Fuel Price, Unemployment)

### 3. Exploratory Data Analysis (EDA)

* Visualized total weekly sales over time
* Identified trends and seasonality in sales patterns

### 4. Modeling Approach

Two regression models were used:

* Linear Regression (baseline model)
* Random Forest Regressor (non-linear model)

### 5. Evaluation Metrics

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)

---

## 📈 Key Results

* Random Forest outperformed Linear Regression in capturing complex patterns
* Sales trends showed clear seasonality and time-based fluctuations
* Economic indicators had measurable influence on sales behavior

---

## 💡 Business Insights

* Certain stores and departments consistently outperform others
* Seasonal effects strongly impact sales volume
* External economic factors (CPI, unemployment) contribute to demand shifts

---

## 🚀 How to Run This Project

1. Download the dataset from Kaggle (Walmart Sales Forecasting dataset)
2. Place the CSV files in the same directory as the notebook
3. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```
4. Open the notebook:

   ```bash
   jupyter notebook
   ```
5. Run all cells sequentially

---

## 📌 Future Improvements

* Implement advanced models (XGBoost, LightGBM)
* Add time-series specific models (ARIMA, Prophet)
* Perform hyperparameter tuning
* Incorporate holiday/event effects more explicitly
* Build a dashboard for business stakeholders

