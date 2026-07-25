# mysql-data-cleaning-portfolio-.

# MySQL Data Cleaning Portfolio Project

## Overview
This project demonstrates data cleaning and manipulation techniques using **MySQL**. Taking a raw dataset of global layoffs, the objective was to clean, standardize, and structure the data into a reliable format for exploratory data analysis (EDA).

## Dataset Source
* Raw Data: Global Layoffs dataset.

## Skills & Techniques Demonstrated
* **Duplicate Removal:** Using CTEs and Window Functions (`ROW_NUMBER()`) to identify and filter out duplicate records.
* **Standardizing Data:** Trimming trailing spaces, fixing typos, and unifying categorical variables (e.g., standardizing industry names).
* **Handling Null/Blank Values:** Querying missing data points and updating records dynamically based on relational logic.
* **Type Conversion:** Converting text-based dates into proper MySQL `DATE` data types.
* **Data Sculpting:** Removing redundant columns and rows that lacked critical metrics.

## File Structure
* `Data_Cleaning_Script.sql`: The complete, commented MySQL script containing all data cleaning queries.

## Conclusion
The resulting clean dataset is fully prepped and optimized for downstream data analysis and visualization in tools like Power BI or Tableau.
