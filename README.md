# Task 02 - Data Cleaning and Preparation

This repository contains the work for **Task 02: Data Cleaning and Preparation** using the Global Superstore dataset.

## 📂 Contents
- `globalsuperstore_clean.csv` → The cleaned dataset with proper headers, missing values handled, duplicates removed, and data types converted.
- `Task02.ipynb` → Google Colab notebook with the full step‑by‑step Python code used for cleaning.

## 📝 Steps Performed
1. Loaded the dataset into Google Colab using Pandas.
2. Assigned proper headers manually to avoid `Unnamed` columns.
3. Dropped empty rows and duplicate records.
4. Converted columns to correct data types:
   - Dates → `datetime`
   - Numeric fields (`sales`, `profit`, `quantity`) → numeric
5. Filled missing values with defaults (e.g., `0` for numeric).
6. Exported the cleaned dataset to a new CSV file.

## 🎯 Goal
The goal of this task is to prepare a clean dataset for further analysis by ensuring:
- Consistent column names
- No duplicates
- Proper handling of missing values
- Correct data types for analysis
## Conclusion
Task 02 successfully cleaned and prepared the Global Superstore dataset for analysis.  
By fixing issues such as extra headers, missing values, wrong data types, and duplicates, the dataset is now consistent, reliable, and ready for use in further analytics and visualization.  
The combination of the Colab notebook and the cleaned CSV ensures both transparency of the process and usability of the final data.
