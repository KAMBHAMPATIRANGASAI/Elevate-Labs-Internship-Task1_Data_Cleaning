# Elevate-Labs-Internship-Task1_Data_Cleaning

# Task 1 – Data Cleaning (Superstore Sales Dataset)

## 📌 Description
This project is part of my Data Analyst Internship Task 1.  
I performed data cleaning on the **Superstore Sales Dataset** (4 years of global sales data).  
The dataset contains information on orders, customers, shipping, and sales performance.  

The goal of this task is to:
- Understand the raw dataset structure
- Identify and handle missing values
- Remove duplicates
- Standardize categorical values
- Convert date formats
- Save and provide a cleaned dataset ready for analysis

---

## 📂 Dataset
- Original dataset: [Superstore Sales Dataset (Kaggle)](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting)
- Cleaned dataset is included in this repository.

---

## 🔧 Cleaning Steps Performed
1. Removed 11 rows with missing `Postal Code`.
2. Removed duplicate rows.
3. Standardized categorical text columns (converted to lowercase, stripped spaces).
4. Converted `Order Date` and `Ship Date` to datetime format.
5. Renamed all columns to lowercase with underscores for consistency.
6. Saved final cleaned dataset as `cleaned_superstore_sales.csv`.

---

## 📑 Files in this Repository
- `superstore_sales.csv` → Original dataset  
- `cleaned_superstore_sales.csv` → Cleaned dataset  
- `data_cleaning.ipynb` → Jupyter Notebook with cleaning process  
- `README.md` → Documentation of the task

---

## 🚀 Outcome
The cleaned dataset is now consistent, complete, and ready for further analysis (e.g., sales trends, forecasting, customer segmentation).
