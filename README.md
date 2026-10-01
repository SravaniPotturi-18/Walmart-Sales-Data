# Task 1: Data Cleaning and Preprocessing

## 📌 Project Overview

This project focuses on cleaning and preprocessing a raw retail dataset using Python and Pandas.

The main objective was to identify and handle missing values, duplicate records, inconsistent data formats, and incorrect data types to prepare the dataset for further analysis.

## 📊 Dataset

The dataset contains **8,190 records and 12 columns** related to store-level information.

### Columns

- Store
- Date
- Temperature
- Fuel Price
- MarkDown1
- MarkDown2
- MarkDown3
- MarkDown4
- MarkDown5
- CPI
- Unemployment
- IsHoliday

## 🛠️ Tools Used

- Python
- Pandas
- Google Colab
- GitHub

## 🧹 Data Cleaning Process

The following preprocessing steps were performed:

1. Loaded the raw CSV dataset using Pandas.
2. Inspected the dataset structure, columns, and data types.
3. Checked for missing values.
4. Identified `NA` values in the Markdown columns.
5. Replaced missing Markdown values with `0`.
6. Checked for duplicate records.
7. Removed duplicate records if present.
8. Converted the `Date` column into a proper datetime format.
9. Converted numerical columns into appropriate numeric data types.
10. Standardized the `IsHoliday` values into a consistent `TRUE/FALSE` format.
11. Identified missing values in `CPI` and `Unemployment`.
12. Filled missing `CPI` and `Unemployment` values using their respective median values.
13. Performed a final check for missing values and duplicate records.
14. Exported the cleaned dataset as `cleaned_dataset.csv`.

## ✅ Final Result

After preprocessing:

- **Rows:** 8,190
- **Columns:** 12
- **Duplicate rows:** 0
- **Missing values:** 0
- **Cleaned dataset:** `cleaned_dataset.csv`

The cleaned dataset is now ready for further analysis and visualization.

## 📁 Project Files

```text
Task-1-Data-Cleaning/
│
├── README.md
├── cleaned_dataset.csv
├── data_cleaning.py
└── screenshots/
