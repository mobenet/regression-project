

# 🛍️ Daily Store Sales Prediction – Regression Project

## 📌 Project Overview

This project tackles a real-world **regression problem**: predicting the **daily sales** of different stores based on various characteristics of the shop and contextual data.

You are provided with:

* **Training data** (640,841 entries) containing:
* **Real-life data** (≈70,000 entries) without sales values.
  * This dataset is used to test your model's ability to generalize and predict unseen data.

The goal is to build a regression model that can accurately estimate sales values and deliver predictions with a high **R² score**.

---

## Objective

*  **Predict the `sales` column** using store features and daily information.
*  Deliver a **.csv file** with predicted `sales` values for the real-life data.
*  Estimate and report your model’s **R² score** on the test set.

---

## Tools & Technologies

* Python (pandas, numpy, sklearn, matplotlib)
* Regression techniques: Linear Regression
* Data preprocessing and feature engineering
* Model evaluation with R², RMSE

---

## Pipeline Overview

1. **Exploratory Data Analysis (EDA):**

   * Visual inspection of distributions and missing values.
   * Understand the relationship between variables and sales.

2. **Data Cleaning & Preprocessing:**

   * Handling missing or invalid values (e.g. 'NA', '?', etc.).
   * Encoding categorical variables (e.g. `state_holiday`).
   * Feature selection and removal of redundant columns (e.g. `date`).
   * Standardization with MinMaxScaler.

3. **Modeling:**

   * Training multiple regression models (Linear, Ridge, Decision Tree).
   * Comparing performance metrics.
   * Selecting the best-performing model.

4. **Prediction:**

   * Using the selected model to predict `sales` for the real-life dataset.
   * Saving the output in `.csv` format with an added `sales` column.

5. **Evaluation:**

   * R² Score and RMSE reported for model performance.
