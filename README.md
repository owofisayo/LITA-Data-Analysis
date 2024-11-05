# LITA-Data-Analysis

### What is Data Analysis

Data Analysis involves inspecting the data, cleaning, transforming and moulding the data to discover useful information, draw conclusion and support decision making.

Every Data Analysit work with ETL
ETL means- Extract, Transform and Load

### Why is Data Analysis Important
1. Data Analysis helps business make informed decision, understand customer behaviour, improve operations and predict the future trends
2. Helps organisations make decision based on actual data rather than guess work
3. Identify bottlenecks and inefficiences in processes, leading to optimiazation and cost reduction

### Introduction to Excel
#### Microsoft Excel is one the tools use in Data Analysis. 

Microsoft Excel is a spreadsheet application that is used to store, manage and analyze data.

### Indroduction to SQL
#### What is SQL

SQL stands for Structure Query Language
It is used for storing and managing data in Relational Database Management System (RDBMS). SQL also allows users to query the database in a number of ways using english-like statement
#### SQL Codes Sample
1. SELECT statements with fltering, sorting and grouping
2. JOINs (INNER, OUTER, FULL) and subqueries
3. Aggregate functions (SUM, AVG, MAX)
4. Data Manipulation (INSERT, UPDATE, DELETE)
#### SQL Queries
1. Querying employees data

   SELECT *
   FROM employees
   WHERE salary > 5000
   ORDER BY last_name

2. Analyzing sales data

SELECT product_name, SUM(sales_amount) AS total_sales FROM sales
  GROUP BY product name
  ORDER BY total sales DESC

4. Database Design

   CREATE TABLE customers (
   id INT PRIMARY KEY,
   name VARCHAR (255),
   email VARCHAR (255),
   )

