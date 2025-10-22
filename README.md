# SQL-Case-Studies
Demonstration of advanced SQL queries for business case studies (Retail &amp; HR).
🗄️ SQL Data Analysis & Business Case Studies 📊

Project Summary: A collection of SQL scripts demonstrating proficiency in database management, data manipulation (DML), and complex query writing to solve diverse business problems across retail/sales and Human Resources (HR) domains.

**1. Project Overview 🌟**

  This repository showcases hands-on experience in extracting business intelligence using ANSI SQL. It focuses on translating specific business questions into efficient database queries, demonstrating mastery of aggregate functions, relationship management (Joins), and advanced features like User-Defined Functions (UDFs) and the ROLLUP operator.

**2. Case Studies Covered 🔑**

 The repository contains solutions for two distinct case studies:

  **Case Study 1:** Retail Sales and Profit Analysis (SQLQuery Case study-1.sql)

   Tables: Location, Product, Fact (Sales/Expenses).

  Key Problems Solved: Calculating total profit by state, determining minimum/maximum sales metrics, calculating average inventory per product, and using the ROLLUP operator for hierarchical reporting (Date, ProductId, Week).

  Advanced Techniques: Demonstrated the creation and use of a custom User-Defined Function (UDF) to filter product data.

**Case Study 2:** Employee Management System (SQLQuery Case Study_2.sql)

   Tables: LOCATION, DEPARTMENT, JOB, EMPLOYEE.

   Key Problems Solved: Database design using DDL (CREATE TABLE with Primary/Foreign Keys), DML (INSERT, UPDATE), and complex querying for HR insights.

   Advanced Techniques: Used Subqueries to find employees based on job title, location, and department, and wrote queries to identify departments with zero employees.

**3. Technical Implementation 💻**

  Technologies Used

  Language: SQL (T-SQL/Generic ANSI SQL dialect used for execution).

  Core Skills: DDL, DML, Aggregate Functions (SUM, AVG, MIN, MAX, COUNT), JOIN operations, GROUP BY, HAVING, Subqueries (Scalar and Correlated), UNION/INTERSECT, and Transaction Management (UPDATE/DELETE).

**4. File Structure 📂**

.
├── SQLQuery Case study-1.sql       # Retail/Sales Data Analysis Queries
├── SQLQuery Case Study_2.sql       # HR/Employee Management Queries
└── README.md                       # Project documentation (This file)



**5. How to Use ⚙️**

   Environment: Open a SQL environment (e.g., SQL Server Management Studio, Azure Data Studio, MySQL Workbench).

   Case Study 2 Setup: Run the DDL and INSERT statements at the beginning of SQLQuery Case Study_2.sql to create the necessary tables and populate them with sample data.

   Run Queries: Execute the individual queries in either file to see the results and the demonstration of the SQL concepts.
