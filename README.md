# 🌍 International Debt Analysis using SQL

A SQL-based data analysis project that explores international debt statistics across **124 countries** using **PostgreSQL**. The project demonstrates how SQL can be used to extract meaningful insights from real-world financial data through aggregation, filtering, sorting, and ranking techniques.

## 📌 Project Overview

This project analyzes global debt data to answer key questions such as:

- What is the total debt recorded across all countries?
- Which country has the highest debt?
- Which debt indicators occur most frequently?
- How does debt vary across different countries and indicators?

The analysis is performed entirely using **SQL queries** in **PostgreSQL**.

## 🛠️ Technologies Used

- PostgreSQL
- SQL
- pgAdmin (or any PostgreSQL client)

## 📂 Dataset

The dataset contains international debt statistics for **124 countries**, with information including:

- Country Name
- Country Code
- Debt Indicator Name
- Indicator Code
- Debt Amount

## 🔍 SQL Concepts Applied

- `SELECT`
- `WHERE`
- `ORDER BY`
- `GROUP BY`
- `LIMIT`
- Aggregate Functions:
  - `SUM()`
  - `AVG()`
  - `COUNT()`
  - `MAX()`
- Aliasing
- Filtering and Sorting

## 📈 Key Analysis Performed

- Calculated the **total global debt** across all countries.
- Identified the **country with the highest debt**.
- Found the **most frequently recorded debt indicator**.
- Compared debt values across countries using grouping and sorting.
- Extracted meaningful insights through filtering and ranking operations.

## 📊 Key Results

- 🌎 Total global debt analyzed: **~$3.08 Trillion**
- 🌍 Countries analyzed: **124**
- 🏆 Identified the country with the highest recorded debt.
- 📌 Determined the most common debt indicator in the dataset.

## 📁 Repository Structure

```
International-Debt-Analysis/
│── dataset/
│   └── international_debt.csv
│
│── queries/
│   ├── 01_total_debt.sql
│   ├── 02_country_with_max_debt.sql
│   ├── 03_most_common_indicator.sql
│   ├── 04_average_debt.sql
│   └── ...
│
├── README.md
```

## 🚀 Learning Outcomes

Through this project, I gained hands-on experience with:

- Writing efficient SQL queries
- Performing data aggregation and analysis
- Working with PostgreSQL databases
- Extracting business insights from structured datasets
- Applying SQL for real-world financial data analysis

## 📬 Author

**Ashit Yadav**

B.Tech, Civil Engineering  
Indian Institute of Technology Kanpur
