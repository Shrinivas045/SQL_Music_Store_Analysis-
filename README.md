# 🎵 Music Store Data Analysis – SQL Project

This project demonstrates end-to-end analysis of a fictional digital music store database using **SQL**. It involves solving a set of business questions categorized by difficulty (Easy, Moderate, Advanced) using real-world analytical approaches and SQL techniques.

---

## 🧠 Objective

To explore and analyze customer behavior, music trends, sales performance, and artist contribution using SQL queries. The focus is on gaining business insights such as:

- Who are the best customers?
- Which countries and cities generate the most revenue?
- What music genres are most popular?
- Which artists produce the most rock music?
- How much is each customer spending on each artist?

---

## 🛠️ Tools Used

- **SQL (PostgreSQL/MySQL syntax)**  
- Data queried from relational tables like: `customer`, `invoice`, `invoice_line`, `track`, `artist`, `album`, `genre`, and `employee`

---

## 📂 Project Structure

### Question Set 1 – Easy
Basic queries to understand customer spending and invoice trends:
- Senior-most employee
- Countries with most invoices
- Top 3 invoice totals
- City with highest revenue
- Best customer by total spend

### Question Set 2 – Moderate
Intermediate analysis involving joins and filters:
- Rock music listeners (with email and genre)
- Top 10 rock artists by number of tracks
- Tracks longer than average length

### Question Set 3 – Advanced
Advanced queries using CTEs and window functions:
- Customer spending by artist
- Most popular genre by country
- Top customer per country based on spending

---

## 📊 Sample SQL Techniques Used

- `JOIN`, `GROUP BY`, `ORDER BY`, `LIMIT`
- Aggregate functions: `SUM()`, `COUNT()`, `AVG()`
- `CTE` (Common Table Expressions)
- `RANK()` window function for top-N analysis
- Subqueries for comparisons (e.g., average track length)

---

## 📝 How to Use

1. Open the SQL file `query.txt` in your database tool (e.g., DBeaver, pgAdmin, MySQL Workbench)
2. Run the queries one by one after connecting to the sample music store database
3. Analyze the output for insights as described in each question



## 📎 Related Skills

- SQL for Data Analysis
- Business Intelligence (BI)
- Data Exploration & Reporting
- Dashboard Prototyping (Power BI, Tableau)
- ETL & Data Cleaning (Python, Excel)

---


