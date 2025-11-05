## DataBase_Testing_SQL_Practice_Project

###  By: Pooja Parashar  
**Role Target:** Software QA Tester / Database Tester

---

##  Project Overview
This project demonstrates my ability to test and validate database logic using SQL.  
It simulates real QA testing scenarios involving a **Awesome Chocolates Sales database** with four tables:

- **Geo**
- **People**
- **Products**
- **Sales**

---

## Key Testing Concepts Covered
- **Data Validation Testing:** Ensuring data accuracy using `WHERE`, `BETWEEN`, and comparison operators  
- **Functional Testing with SQL:** Verifying business rules such as sales thresholds and conditions  
- **Join Testing:** Cross-table verification between `sales`, `people`, and `products`  
- **Aggregate Testing:** Using `COUNT()`, `SUM()`, `GROUP BY`, and `HAVING` to check totals  
- **Date Validation:** Filtering records using `YEAR()`, `MONTH()`, and `WEEKDAY()` functions  
- **Negative Testing:** Identifying missing or invalid data using `NOT IN` and `LEFT JOIN IS NULL`

---

## 📂 Files Included
| File Name | Description |
|------------|-------------|
| `Awesome_Chocolates_Sales_Query.sql` | Full SQL script for testing and validation |
| `README.md` | Documentation explaining QA testing use case |

---

##  How to Use
1. Import sample tables (`geo`, `people`, `products`,`sales`) into MySQL or SQLite.
2. Copy and execute the queries from `sales_analysis_testing_queries.sql`.
3. Observe how SQL queries can detect data issues, validate joins, and verify business logic.

---

##  Tools & Environment
- **Database:** MySQL (tested on MySQL 8.0)
- **Use Case:** Data validation for QA / database testing
- **Focus:** Query testing, data consistency, and backend verification

---

## Example QA Scenarios
- Verify that every salesperson has at least one sale.
- Check if any sale exceeds 10,000 in amount.
- Identify sales data missing product or salesperson references.
- Validate correct product counts per month.

---

**This project showcases my SQL testing and database validation skills, useful for QA & Data Tester roles.**
