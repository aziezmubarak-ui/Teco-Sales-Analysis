# Teco Sales Analysis & Predictive Modeling

This repository contains a comprehensive data science project focused on sales transaction data from "Teco," a beverage outlet. The project covers Exploratory Data Analysis (EDA), Market Basket Analysis (Association Rules), and Time-Series Sales Forecasting using XGBoost.

## 📌 Project Overview
The objective is twofold:
1. **Understanding Customer Behavior:** Identify product associations (bundling opportunities) using the Apriori algorithm.
2. **Sales Forecasting:** Build a machine learning model to predict future sales performance based on historical time-series data.

## 📊 Key Features
* **Time-Series EDA:** Analysis of sales frequency by hour and daily transaction trends.
* **Market Basket Analysis:** Implementation of `mlxtend` to find association rules (Support, Confidence, and Lift) between drinks and extra toppings.
* **Advanced Feature Engineering:** Creating time-based features (day, month, hour) for predictive modeling.
* **Machine Learning:** Training an **XGBoost Regressor** to forecast sales values.
* **Model Evaluation:** Performance tracking using Root Mean Squared Error (RMSE) on test data.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** * Data Manipulation: `Pandas`, `NumPy`
    * Visualization: `Matplotlib`, `Seaborn`
    * Data Mining: `MLxtend` (Apriori & Association Rules)
    * Machine Learning: `XGBoost`, `Scikit-learn`

## 📈 Insights & Results
* **Peak Hours:** Identified that sales significantly peak during the evening (e.g., around 19:00).
* **Product Bundling:** Discovered frequent itemsets such as specific beverage variants paired with "Extra syrup" or "Extra Espresso Shots."
* **Model Performance:** The XGBoost model successfully tracked training trends, though further hyperparameter tuning is suggested to minimize test-set RMSE ($490,792.62).

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/aziezmubarak-ui/Teco-Sales-Analysis.git](https://github.com/aziezmubarak-ui/Teco-Sales-Analysis.git)
