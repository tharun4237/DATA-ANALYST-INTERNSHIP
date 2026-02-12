# DATA-ANALYST-INTERNSHIP
DATA-ANALYST-INTERNSHIP-Task1
Task 1 – Data Cleaning and Preprocessing
Project Overview

This project focuses on cleaning and preprocessing a raw dataset to prepare it for analysis and modeling.

The dataset used in this task:

Mall Customers Dataset

The objective was to identify and resolve common data quality issues such as:

Missing values

Duplicate records

Inconsistent formats

Incorrect data types

Outliers

Files Included

Data_Cleaning_and_Preprocessing.py
Python script containing complete data cleaning code

Mall_Customers.csv
Original raw dataset

cleaned_mall_customers.csv
Final cleaned dataset generated after running the script

Tools Used

Python

Pandas

NumPy

Data Cleaning Steps Performed
1. Dataset Exploration

Used head(), info(), and describe() to understand the dataset

Checked missing values using isnull().sum()

Checked duplicate records using duplicated()

2. Missing Value Treatment

Verified that the dataset contains no missing values

Confirmed data completeness

3. Duplicate Removal

Checked duplicate rows using duplicated()

No duplicate records were found

4. Column Name Standardization

Converted column names to lowercase

Removed extra spaces

Replaced spaces with underscores

Removed special characters

Example:
Annual Income (k$) → annual_income_k$

5. Text Standardization

Converted gender values to lowercase

Removed leading and trailing spaces

Example:
Male, Female → male, female

6. Data Type Correction

Ensured numeric columns are properly formatted as integers

Verified column data types using info()

7. Outlier Detection

Used the IQR (Interquartile Range) method to detect extreme values in:

Age

Annual Income

Spending Score

This ensures the dataset is reliable for further analysis.

Final Outcome

Clean dataset with no missing values

Duplicate records verified and handled

Standardized column names

Consistent text formatting

Correct data types applied

Outliers identified

The dataset is now ready for data analysis, visualization, or machine learning modeling.
