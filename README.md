# Cafe Sales Dataset Preparation & EDA

## 📋 Activity Overview
This project involves inspecting a raw tabular dataset, identifying data-quality and missing-value issues, performing exploratory data analysis (EDA), handling missing values, encoding categorical features, scaling numerical features, and preparing a clean dataset for machine learning workflows. 

## 📊 Dataset Information
* **Dataset:** Cafe Sales Transactions Dataset (sourced from open-source repository archive)
* **File Type:** CSV
* **Rows:** 10,000 | **Columns:** 8

## 🛠️ Work Completed (Workflow Summary)
1. **Dataset Inspection:** Loaded the data, inspected the first/last rows, column names, and data types (`df.info()`).
2. **Summary Statistics:** Examined numerical and categorical columns to uncover data anomalies (such as text errors in numerical columns and `UNKNOWN` values).
3. **Missing Value Handling:** Quantified missing values and imputed numerical columns using the median and categorical columns using the mode.
4. **Data Consistency & Cleaning:** Checked for duplicate records and standardized text formats across categorical attributes.
5. **Exploratory Data Analysis (EDA):** Generated visualizations (such as transaction counts by payment method) to analyze sales distributions.
6. **Feature Encoding & Scaling:** Performed one-hot encoding on categorical features and applied standard scaling (`StandardScaler`) to numerical features.
7. **Export:** Saved the final prepared dataset as `cleaned_cafe_sales.csv`.

## 📁 Repository Contents
* `cafe_sales_preparation.ipynb`: The complete Google Colab notebook containing all Python code and visible outputs.
* `cleaned_cafe_sales.csv`: The final processed and cleaned dataset.

## 📝 Acknowledgements & Faculty Reference
This project was completed as part of the Machine Learning CIE 2 activity. Faculty reference and Machine Learning learning resources: [https://github.com/Princy2129](https://github.com/Princy2129).