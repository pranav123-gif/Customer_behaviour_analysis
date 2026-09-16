# Customer_behaviour_analysis
Data analytics project showcasing behaviour analysis using python,sql and powerbi.

 📊 Data Analytics Project
Overview

This project demonstrates an end-to-end Data Analytics workflow, starting from raw dataset loading and data cleaning to SQL analysis, Power BI visualization, reporting, and presentation.

The goal is to transform raw data into meaningful insights and business-ready visualizations using Python, SQL, and Power BI.

🔄 Project Workflow

Dataset → Python → EDA → Data Cleaning → SQL Analysis → Power BI Dashboard → Report → Presentation

📁 Dataset

The project uses a structured dataset containing relevant records for analysis.

The dataset was:

Loaded and inspected using Python
Checked for missing values and duplicates
Cleaned and prepared for analysis
Explored using statistical and visual techniques
Stored/processed for SQL-based analysis
Used as the source for the Power BI dashboard

Dataset: your_dataset.csv
Note: Replace this filename with your actual dataset name.

🛠️ Tools & Technologies
Tool	Purpose
Python	Data loading, cleaning and analysis
Pandas	Data manipulation
NumPy	Numerical operations
Matplotlib	Data visualization
Seaborn	Statistical visualization
PostgreSQL	SQL analysis and database queries
MySQL	SQL analysis
SQL Server	SQL analysis
Power BI	Interactive dashboard
Gamma	Project presentation
MS Excel	Supporting data preparation/analysis
🚀 Project Steps

1. Load Dataset

The dataset was imported into Python using Pandas.

import pandas as pd

df = pd.read_csv("your_dataset.csv")

print(df.head())
print(df.shape)
print(df.info())

2. Exploratory Data Analysis (EDA)

EDA was performed to understand the structure, patterns, and characteristics of the dataset.

Key activities included:

Dataset dimensions
Data types
Missing-value analysis
Duplicate-value detection
Descriptive statistics
Unique-value analysis
Distribution analysis
Relationship analysis
Visualizations

The following charts were used where applicable:

Histogram
KDE Plot
Boxplot
Countplot
Barplot
Scatterplot
Heatmap

3. Data Cleaning

The dataset was prepared for analysis by:

Removing duplicate records
Handling missing values
Correcting data types
Removing unnecessary columns
Handling inconsistent values
Formatting dates and numerical fields
Checking for outliers where required

Example:

df = df.drop_duplicates()
df = df.dropna()

4. SQL Analysis

The cleaned dataset was imported into a relational database for SQL analysis.

SQL queries were developed using:

PostgreSQL
MySQL
SQL Server

Analysis included:

Aggregations
Filtering
Sorting
GROUP BY
ORDER BY
JOIN
Subqueries
Aggregate functions
Business-related analytical queries

Example:

SELECT category,
       SUM(sales) AS total_sales
FROM sales_data
GROUP BY category
ORDER BY total_sales DESC;

📊 Power BI Dashboard

An interactive Power BI dashboard was created to present the key findings in an easy-to-understand format.

Dashboard Components
KPI cards
Sales/revenue analysis
Category-wise analysis
Trend analysis
Geographic analysis
Customer/segment analysis
Interactive filters and slicers
Charts and tables

The dashboard allows users to interact with the data and quickly identify important trends and patterns.

Dashboard Preview

Add your Power BI dashboard screenshot here.

![Power BI Dashboard](images/dashboard.png)

📈 Results & Insights

The project converts raw data into actionable analytical insights.

Key outcomes include:

Identified important trends and patterns in the dataset
Analyzed performance across different categories
Compared key business metrics
Identified high- and low-performing segments
Used SQL to answer analytical questions
Created an interactive dashboard for decision-making
Presented findings through a structured report and presentation

Note: Add your actual numerical findings and business insights here based on your dataset.

📝 Project Report

A detailed project report was prepared covering:

Introduction
Dataset Description
Data Cleaning
Exploratory Data Analysis
SQL Analysis
Power BI Dashboard
Results and Insights
Conclusion

The report documents the complete analytical process and findings.

🎤 Presentation

A project presentation was created using Gamma to communicate the workflow, analysis, dashboard, and key findings.

The presentation covers:

Project objective
Dataset
Methodology
EDA
Data cleaning
SQL analysis
Power BI dashboard
Key insights
Conclusion

📂 Project Structure

Data-Analytics-Project/
│
├── dataset/
│   └── your_dataset.csv
│
├── python/
│   └── data_analysis.ipynb
│
├── sql/
│   ├── postgresql_queries.sql
│   ├── mysql_queries.sql
│   └── sql_server_queries.sql
│
├── powerbi/
│   └── dashboard.pbix
│
├── report/
│   └── project_report.pdf
│
├── presentation/
│   └── project_presentation.pdf
│
├── images/
│   └── dashboard.png
│
└── README.md

▶️ How to Run

Step 1 — Clone the Repository
git clone https://github.com/yourusername/data-analytics-project.git
cd data-analytics-project

Step 2 — Install Python Libraries
pip install pandas numpy matplotlib seaborn

Step 3 — Run Python Analysis

Open the Jupyter Notebook:

jupyter notebook

Run the notebook to perform:

Data Loading → EDA → Cleaning → Visualization

Step 4 — Run SQL Queries

Import the cleaned dataset into your preferred database:

PostgreSQL
MySQL
SQL Server

Then execute the SQL scripts available in the sql/ folder.

Step 5 — Open Power BI

Open:

powerbi/dashboard.pbix

Refresh the data if required and explore the interactive dashboard.

Step 6 — Review Report & Presentation

The completed report and Gamma presentation are available in their respective folders.

🎯 Skills Demonstrated
Data Cleaning
Exploratory Data Analysis
Python
Pandas & NumPy
Data Visualization
SQL
PostgreSQL
MySQL
SQL Server
Power BI
Dashboard Development
Data Interpretation
Business Reporting
Data Storytelling
Presentation Development

📌 Conclusion

This project demonstrates a complete end-to-end data analytics pipeline, from raw data preparation to business intelligence and presentation.

It highlights practical skills in Python, EDA, data cleaning, SQL, Power BI, reporting, and data storytelling, making it suitable as a portfolio project for Data Analyst / Business Analyst / BI Analyst roles.

👤 Author

Badisa Pranava Sai

Data Analytics | Python | SQL | Power BI
