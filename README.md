# ⚽ SQL Soccer Analytics – Advanced Queries with CTEs & Window Functions

## 📌 Project Overview

This project demonstrates advanced SQL techniques using the **European Soccer Database**.
It focuses on analyzing match data through structured queries involving:

* Common Table Expressions (CTEs)
* Window Functions (OVER, PARTITION BY, RANK)
* CASE Statements
* Subqueries
* Data filtering and transformation

The main goal is to build **real-world analytical queries** similar to those used in data analytics and business intelligence workflows.

---

## 🎯 Key Objectives

* Analyze football match data across seasons and leagues
* Compare team performance (home vs away)
* Identify match outcomes (win/loss/tie)
* Rank matches based on goal differences
* Apply running totals and averages (time-series analysis)
* Build clean and readable SQL using CTEs

---

## 📊 Example Analyses

### 🔹 Manchester United Match Analysis

* Filter matches from the **2014/2015 season**
* Identify **losses only**
* Rank matches based on **goal difference**
* Compare performance as home vs away team

### 🔹 Legia Warszawa Performance

* Partition data by **season and month**
* Compare match performance against **seasonal averages**

### 🔹 FC Utrecht Time-Series Analysis

* Running total of goals (cumulative)
* Running average of performance over time
* Forward and backward window analysis

---

## 🧠 SQL Concepts Covered

### ✅ CTEs (Common Table Expressions)

Used to break complex queries into logical steps.

### ✅ Window Functions

```sql
AVG(...) OVER()
RANK() OVER(ORDER BY ...)
SUM(...) OVER(ROWS BETWEEN ...)
```

### ✅ PARTITION BY

Segment data by:

* Season
* Month
* Team

### ✅ CASE Statements

Used to classify match outcomes:

* Win
* Loss
* Tie

### ✅ Subqueries

* Scalar subqueries
* Correlated subqueries
* Subqueries in FROM

---

## 🛠️ Technologies Used

* SQL (PostgreSQL / compatible dialects)
* Jupyter Notebook (SQL cells)
* European Soccer Database

---

## 🚀 Why This Project Matters

This project simulates real-world data analysis tasks such as:

* KPI tracking
* Performance comparison
* Trend analysis
* Feature engineering

It is especially useful for:

* Aspiring **Data Analysts**
* SQL learners aiming for **advanced level**
* Anyone preparing for **data interviews**

---



---

## ✨ Highlights

* Clean and readable SQL structure
* Real dataset with meaningful insights
* Covers beginner → advanced SQL progression
* Strong portfolio-ready project

---

## 📬 Contact

Feel free to reach out or contribute!
Let's build better data skills together 🚀

---

