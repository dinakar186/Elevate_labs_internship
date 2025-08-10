Day 1 – Data Cleaning & Preprocessing

Files

raw_sales_data.csv – Original dataset before cleaning.
cleaned_sales_data.csv – Final dataset after cleaning with Pandas.
cleaning_summary.txt – Short report summarizing cleaning steps performed.
data_cleaning.ipynb – Google Colab notebook containing all Python code.

Steps Performed

Removed duplicate rows.
Dropped ADDRESSLINE2 column due to excessive null values.
Filled missing values in STATE, POSTALCODE, and TERRITORY columns.
Standardized column names to lowercase with underscores.
Converted ORDERDATE column to datetime format (dd-mm-yyyy).
Corrected data types for numeric columns like quantityordered, priceeach, and sales.

Tools Used

Python with Pandas library
Google Colab environment
