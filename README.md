# 📊 SalesPulse – Python Data Cleaning Analysis
![Background Image](https://github.com/MadhurDwivedi/SalesPulse-Python_Data_Cleaning_Analysis/blob/main/Background%20Image.jpg)
## 📌 Project Objective
The objective of this project is to build an automated data cleaning and preprocessing application using Python that handles duplicate records, missing values, and data quality issues in sales datasets.

This project focuses on simulating a real-world data preparation workflow by allowing users to provide dataset paths and names dynamically, ensuring clean, analysis-ready data for downstream analytics and reporting.

---

## 🗂️ Dataset Used
- The project works with sales datasets provided by the user in CSV or Excel format.
- Key characteristics of the dataset:
  - Sales transactional data
  - Mixed data types (numeric & categorical)
  - Presence of duplicate records
  - Missing values across multiple columns
- 🔗 Dataset Link: <a href="https://github.com/MadhurDwivedi/ElectoScope_India_2024/tree/main/Dataset">Dataset</a>

---

## ❓ Business Problem Statement
- Raw sales data often contains duplicates, null values, and inconsistencies that reduce data reliability.
- This project solves the problem by automating data cleaning tasks, ensuring data accuracy, consistency, and usability for analytics and decision-making.

---

## ⚙️ Application Workflow
- The application performs the following steps:
  - Accepts dataset path and dataset name from the user
  - Validates file path and file type (CSV / Excel)
  - Identifies total rows and columns
  - Detects duplicate records
  - Stores all duplicate records separately
  - Removes duplicate rows from the main dataset
  - Identifies missing values across columns
- Handles missing values:
  - Numeric columns → Replaced with column mean
  - Non-numeric columns → Rows dropped
- Exports:
  - Cleaned dataset
  - Duplicate records dataset

---

## 🔍 Data Cleaning & Analysis Tasks
- Duplicate detection and removal
- Missing value identification
- Mean imputation for numeric columns
- Row-level removal for categorical nulls
- Dataset validation and export

---

## ⚙️ Tech Stack
| Component | Technology |
|----------|------------|
| Programming Language | Python |
| Data Handling | Pandas, NumPy |
| File Handling | CSV, Excel (openpyxl, xlrd) |
| OS Operations | os |
| Automation & Delay Simulation | time, random |

---

## 🔍 Project Insights
- Duplicate records can significantly impact sales analysis accuracy
- Mean imputation maintains numerical data continuity
- Early-stage data cleaning improves downstream analytics reliability
- Automated workflows save manual preprocessing time

---

## ✅ Final Conclusion
This project demonstrates how Python can be used to automate end-to-end data cleaning workflows for sales datasets.

By handling duplicates, missing values, and file validation dynamically, the application ensures clean, structured, and analysis-ready data suitable for business intelligence and reporting tasks.

