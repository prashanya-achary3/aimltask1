# aimltask1
data cleaning and data preprocessing
# Titanic Data Cleaning & Preprocessing

This project focuses on cleaning and preprocessing the Titanic dataset using Python, Pandas, NumPy, and Seaborn.

## ✔️ Steps Performed

### 1. Import & Explore Dataset
- Loaded dataset using Pandas  
- Displayed basic info and checked data types  

### 2. Missing Value Handling
- Filled missing values in Age using Median  
- Filled missing values in Embarked with Mode  
- Dropped Cabin (too many missing values)

### 3. Encoding
- Converted Sex to 0/1  
- Converted Embarked into dummy columns (Q, S)

### 4. Normalization
- Standardized numerical features:
  - Age
  - Fare
  - SibSp
  - Parch

### 5. Outlier Detection & Removal
- Used Boxplots to identify outliers  
- Removed outliers in Age and Fare using IQR method  

## ✔️ Final Dataset
- Rows after cleaning: **718**
- Columns: **9**

## Tools Used
- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
