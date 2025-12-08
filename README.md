📊 Customer Behavior Data Analytics Project
🧾 Overview

This project focuses on analyzing customer shopping behavior to uncover insights that support business decision-making.
The workflow includes loading and exploring the dataset in Python, cleaning and preparing the data, running analytical SQL queries using MySQL, and visualizing key results through an interactive Power BI dashboard.

📂 Dataset
Name: Customer Shopping Behavior Dataset
Format: CSV
Rows: ~4,000 records
Columns: Product purchased, customer demographics, purchase amount, review ratings, transaction date, category, and more.
Source: Public dataset
The dataset was used to understand purchasing patterns, customer preferences, and product performance.

🛠 Tools & Technologies
Tool / Language	Purpose
Python (Pandas, NumPy, Matplotlib, Seaborn)	Data loading, cleaning, EDA
Jupyter Notebook	Development & visualization workspace
MySQL	SQL queries & deeper data analysis
SQLAlchemy & PyMySQL	Connect Python to MySQL
Power BI Desktop	Interactive dashboard & storytelling
GitHub	Version control & documentation
🔍 Project Steps
1. Data Loading

Loaded CSV dataset into Python using Pandas
Initial inspection of data structure and data types

2. Exploratory Data Analysis (EDA)

Summary statistics
Feature distributions
Outlier / missing value detection
Understanding relationships using visualizations

3. Data Cleaning

Handling missing / duplicated records
Converting data types (date, numeric fields)
Filtering and validating inconsistent values

4. SQL Analysis

Imported cleaned dataset into MySQL
Performed analytical queries:
Top purchased products
Average review rating by product
High-value customer segments
Monthly purchase trend

5. Power BI Dashboard
Connected cleaned dataset
Built visual analytics with slicers and KPIs
Dashboard includes:
Total Revenue / Orders / Customers summary
Top 5 products by sales
Customer segmentation by spending
Purchase trends over time
Ratings analysis

🧠 Insights & Results

Identified best-performing products and categories
Found spending trends across months and customer groups
Highlighted behavior of repeat vs new customers
Analyzed review patterns affecting product success
These insights help businesses improve product strategy and targeted marketing decisions.

🚀 How to Run This Project
Clone the repository
git clone https://github.com/<username>/<repo-name>.git

Install dependencies
pip install -r requirements.txt
Run analysis

Open the Jupyter notebook:
Customer_Behavior_Analysis.ipynb

SQL queries
Run scripts from /sql/customer_behavior_sql_queries.sql in MySQL

Power BI Dashboard
Open:
PowerBI/Customer_Behavior_Dashboard.pbix

📌 Future Improvements

Predicting customer churn using ML models
Building recommendation system
