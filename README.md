Task 14 – ETL Mini Pipeline
📌 Objective

Build an ETL pipeline using Python (Extract → Transform → Load).

🔹 Extract

Loaded raw dataset from Kaggle

Stored in raw folder

🔹 Transform

Removed duplicates

Handled missing values

Standardized column names

Created derived columns:

sales

cost

margin

high_value_customer flag

🔹 Load

Exported processed CSV

Split into:

customers table

orders table

products table

Loaded data into SQLite database

🔹 Validation

Verified row counts before and after cleaning

Checked null values

Confirmed database tables created successfully

🔹 Tools Used

Python

Pandas

SQLite

Google Colab
