# Beginner SQL Notes

## Overview

This document summarises the beginner SQL concepts that I learned while building a foundation in relational databases using MySQL.

The exercises focus on understanding how to create a database, retrieve data, filter records, group and sort results, compare filtering techniques, and limit query outputs. Each topic is accompanied by a separate SQL script containing practical examples.

---

## Learning Objectives

After completing this section, I was able to:

- Create and initialise a relational database.
- Retrieve data from one or more columns using `SELECT`.
- Filter records using the `WHERE` clause.
- Group and summarise data using `GROUP BY`.
- Sort query results using `ORDER BY`.
- Understand the difference between `WHERE` and `HAVING`.
- Limit query results using `LIMIT`.
- Improve query readability using column aliases.

---

# Beginner SQL Topics

## 1. Creating a Database

**SQL Script:** `01_create_database.sql`

### Concepts Covered

- Creating a database
- Selecting a database
- Creating tables
- Defining primary keys
- Defining data types
- Inserting sample data

### Key SQL Statements

- `CREATE DATABASE`
- `USE`
- `CREATE TABLE`
- `INSERT INTO`

### Learning Outcome

Learned how to initialise a relational database and populate it with sample data for future SQL practice.

---

## 2. SELECT Statement

**SQL Script:** `02_select_statement.sql`

### Concepts Covered

- Retrieving all columns
- Selecting specific columns
- Arithmetic calculations
- DISTINCT values

### Key SQL Statements

- `SELECT`
- `DISTINCT`

### Learning Outcome

Learned how to retrieve information from database tables and display only the required columns or unique values.

---

## 3. WHERE Clause

**SQL Script:** `03_where_clause.sql`

### Concepts Covered

- Filtering records
- Comparison operators
- Logical operators

### Key SQL Statements

- `WHERE`
- `AND`
- `OR`
- `NOT`
- `LIKE`
- `IN`
- `BETWEEN`

### Learning Outcome

Learned how to retrieve only records that satisfy specified conditions.

---

## 4. GROUP BY and ORDER BY

**SQL Script:** `04_group_by_order_by.sql`

### Concepts Covered

- Aggregating records
- Grouping data
- Sorting query results

### Key SQL Statements

- `GROUP BY`
- `ORDER BY`
- `COUNT()`
- `SUM()`
- `AVG()`
- `MIN()`
- `MAX()`

### Learning Outcome

Learned how to summarise datasets and organise query outputs for easier interpretation.

---

## 5. HAVING vs WHERE

**SQL Script:** `05_having_vs_where.sql`

### Concepts Covered

- Filtering before grouping
- Filtering after grouping

### Key SQL Statements

- `WHERE`
- `HAVING`

### Learning Outcome

Learned the difference between filtering individual rows before aggregation and filtering grouped results after aggregation.

---

## 6. LIMIT and Aliasing

**SQL Script:** `06_limit_aliasing.sql`

### Concepts Covered

- Returning a subset of records
- Renaming columns
- Improving query readability

### Key SQL Statements

- `LIMIT`
- `AS`

### Learning Outcome

Learned how to simplify query outputs and control the number of returned records.

---

# SQL Skills Developed

Throughout these beginner exercises, I practised:

- Database creation
- Table creation
- Data insertion
- Data retrieval
- Data filtering
- Data grouping
- Data sorting
- Aggregate functions
- Logical operators
- Query optimisation for readability

---

# Beginner SQL Files

```text
01_create_database.sql
02_select_statement.sql
03_where_clause.sql
04_group_by_order_by.sql
05_having_vs_where.sql
06_limit_aliasing.sql
```

---

# Summary

This beginner section establishes the core SQL skills required for data analysis. These concepts form the foundation for more advanced topics such as joins, subqueries, string functions, window functions, Common Table Expressions (CTEs), stored procedures, and triggers, which are covered in the Intermediate and Advanced sections of this repository.
