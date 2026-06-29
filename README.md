# Mall Customers Data Cleaning Project

## 📌 Project Overview

This project demonstrates the process of cleaning and preprocessing the **Mall Customers Dataset** using **Python** and **Pandas**. The objective was to inspect the dataset for common data quality issues, standardize its structure, and prepare it for further analysis or machine learning.

---

## 🎯 Objective

The main objectives of this project were to:

- Load and inspect the dataset
- Check for missing values
- Identify and remove duplicate records
- Standardize column names
- Verify data types
- Validate categorical values
- Generate summary statistics
- Export a cleaned dataset

---

## 📂 Dataset Information

- **Dataset Name:** Mall Customers Dataset
- **Source:** Kaggle
- **Rows:** 200
- **Columns:** 5

### Features

| Column | Description |
|---------|-------------|
| CustomerID | Unique customer identifier |
| Gender | Customer gender |
| Age | Customer age |
| Annual Income (k$) | Annual income in thousands of dollars |
| Spending Score (1-100) | Spending score assigned by the mall |

---

## 🛠 Tools & Libraries

- Python 3
- Pandas
- NumPy
- Jupyter Notebook

---

## 🧹 Data Cleaning Process

The following preprocessing steps were performed:

- Imported the dataset using Pandas
- Inspected dataset structure using `.info()`
- Examined the first and last records
- Checked for missing values using `.isnull().sum()`
- Verified duplicate records using `.duplicated().sum()`
- Renamed column headers using lowercase and underscores
- Verified and validated data types
- Checked categorical values for consistency
- Generated descriptive statistics using `.describe()`
- Exported the cleaned dataset

---

## ✅ Results

After inspection, the dataset was found to be in excellent condition.

| Check | Result |
|--------|--------|
| Missing Values | None |
| Duplicate Rows | None |
| Incorrect Data Types | None |
| Inconsistent Gender Values | None |
| Extra Spaces | None |

The cleaned dataset is ready for:

- Exploratory Data Analysis (EDA)
- Data Visualization
- Customer Segmentation
- Machine Learning

---

## 📁 Project Structure

```
Mall_Customer_Data_Cleaning/
│
├── data/
│   └── Mall_Customers.csv
│
├── cleaned_data/
│   └── cleaned_mall_customers.csv
│
├── notebook/
│   └── Mall_Customer_Cleaning.ipynb
│
├── README.md
│
└── requirements.txt
```

---

## 📊 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Data Inspection
- Pandas
- Data Validation
- Data Wrangling
- Python Programming

---

## 🚀 Future Work

Possible extensions to this project include:

- Exploratory Data Analysis (EDA)
- Customer Segmentation using K-Means Clustering
- Data Visualization with Matplotlib and Seaborn
- Machine Learning Model Development

---
