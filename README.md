# SQL---music-store-sql-project-New

🎵 Music Store SQL Analysis

A SQL portfolio project analyzing a digital music store database with 30 business questions answered using SQL Server. Each question is in its own file for easy browsing and learning.


📊 Project Overview
This project demonstrates SQL skills through real business analysis on a music store's sales data. It progresses from basic queries to advanced window functions and CTEs — perfect for showcasing data analyst capabilities.
Dataset Highlights

11 tables with full relational integrity
3,503 tracks across 25 genres
614 invoices worth $4,709.43 in total revenue
59 customers spanning 24 countries
Time range: January 2017 – December 2020

📥 Dataset
This project uses a digital music store dataset from Kaggle
🔗 Download the dataset here: Music Data Store(https://www.kaggle.com/datasets/bvenkateshnaidu/music-data)

🗂️ Repository Structure
music-store-sql/
│
├── README.md               ← You are here
├── easy/                   ← 10 fundamental SQL queries
├── moderate/               ← 10 intermediate queries
└── advanced/               ← 10 advanced queries
Each .sql file contains:

The business question being answered
SQL concepts demonstrated
The full solution
Expected sample results


🟢 Easy Questions (Fundamentals)

🟡 Moderate Questions (Joins & Subqueries)

🔴 Advanced Questions (CTEs & Window Functions)


💡 Key Insights from the Analysis
🔍 FindingInsight🎸 Top genreRock dominates — top genre in 23 of 24 countries👑 Top artistQueen generated the most revenue ($190.08)🌍 Best marketUSA has the most invoices; Czech Republic spends most per order👤 Top customerFrantišek Wichterlová spent $144.54 across 18 invoices📉 Dead inventory1,697 tracks (48%) have never been purchased🌎 Coverage gap23 of 24 customer countries have no local employees

🚀 How to Run These Queries

Download the dataset from Kaggle
Install SQL Server Express (free) and SSMS
Create a database called MusicStoreDB
Import the CSVs into matching tables
Open any .sql file from easy/, moderate/, or advanced/
Run the query and see the results!


💡 No SQL Server? Try sqliteonline.com — most queries work as-is.


🛠️ SQL Concepts Demonstrated

✅ Joins: INNER, LEFT, multi-table (5+)
✅ Aggregations: COUNT, SUM, AVG, MIN, MAX
✅ GROUP BY with HAVING
✅ Subqueries: scalar, NOT IN, correlated
✅ Date functions: YEAR, MONTH, DATENAME, BETWEEN
✅ String functions: UPPER, SUBSTRING, CHARINDEX, LIKE
✅ CASE WHEN conditional logic
✅ CTEs (WITH clause)
✅ Window functions: ROW_NUMBER, RANK, DENSE_RANK, NTILE, LAG, SUM OVER
✅ Set operators: UNION
✅ Views: CREATE VIEW


👤 Author
Preksha Mehta
🔗 LinkedIn: linkedin.com/in/preksha-mehta
🐙 GitHub: @preksha-246
Feel free to fork, learn from, or contribute to this project!

📄 License
Open-source under the MIT License.
