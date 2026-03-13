# DB Lab 6 – SQL Aggregation using GROUP BY and HAVING

## 📘 About the Assignment
This assignment focuses on practicing SQL aggregate functions and grouped data analysis in Oracle Database. It includes summarizing data using aggregate functions such as COUNT, MAX, MIN, and analyzing grouped data using GROUP BY. It also demonstrates filtering grouped results using the HAVING clause and retrieving analytical information from multiple related tables using JOIN operations with aggregation.

The objective of this lab is to understand how relational databases generate summarized reports from stored data without modifying the underlying tables.

---

## 📂 File Structure
- Question_06.pdf – Contains the list of lab questions provided by the instructor
- Assignment_06_Solution.sql – Contains all SQL queries for Parts A, B, C, D, and E
- README.md – Documentation explaining the assignment

---

## ▶ How to Execute the SQL Scripts
1. Open SQL*Plus or Oracle SQL Developer.
2. Connect to the database using: CONNECT lab/<password>@localhost:1521/xepdb1
3. Open the file `Assignment_06_Solution.sql`.
4. Execute the queries one by one.
5. Verify the results in the output window.

---

## 📝 Assumptions
- Oracle SQL syntax is used.
- All required tables (STUDENT, FACULTY, COURSE, ENROLLMENT) are already created.
- Sample data has been inserted before running the queries.
- Oracle 12c or later version is being used.
- Aggregate functions such as COUNT, MAX, and MIN are used.
- GROUP BY and HAVING clauses are used for grouped analysis.
- Some analytical queries use JOIN operations between related tables.
- No table structure or stored data is modified.
