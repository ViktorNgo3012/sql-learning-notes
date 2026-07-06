
# Intermediate SQL Notes

## Overview

This document summarises the intermediate SQL concepts that I learned using MySQL. Building on the beginner SQL fundamentals, these exercises introduce techniques for combining tables, transforming text data, applying conditional logic, writing nested queries, and performing analytical calculations using window functions.

The examples use the Parks and Recreation sample database to demonstrate practical SQL techniques that are commonly applied in data analysis, reporting, and business intelligence.

---

## Learning Objectives

After completing this section, I was able to:

- Combine related tables using joins.
- Merge query results using `UNION`.
- Manipulate and clean text using SQL string functions.
- Apply conditional logic using `CASE` statements.
- Write subqueries for filtering and aggregation.
- Perform analytical calculations using window functions.
- Rank records and analyse grouped data efficiently.

---

# Intermediate SQL Topics

## 1. Joins

**SQL Script:** `07_joins.sql`

### Concepts Covered

- INNER JOIN
- Self Join
- Joining multiple tables
- Table aliases

### Key SQL Statements

- `INNER JOIN`
- `ON`
- `AS`

### Learning Outcome

Learned how to combine related data from multiple tables using shared keys and how to use self joins to compare records within the same table.

---

## 2. UNION

**SQL Script:** `08_unions.sql`

### Concepts Covered

- Combining multiple query results
- Creating custom labels
- Sorting merged datasets

### Key SQL Statements

- `UNION`
- `ORDER BY`

### Learning Outcome

Learned how to merge multiple result sets into a single query while maintaining a consistent output structure.

---

## 3. String Functions

**SQL Script:** `09_string_functions.sql`

### Concepts Covered

- Measuring string length
- Converting text to upper and lower case
- Removing whitespace
- Extracting substrings
- Replacing characters
- Locating text
- Concatenating strings

### Key SQL Functions

- `LENGTH()`
- `UPPER()`
- `LOWER()`
- `RTRIM()`
- `LEFT()`
- `RIGHT()`
- `SUBSTRING()`
- `REPLACE()`
- `LOCATE()`
- `CONCAT()`

### Learning Outcome

Learned how to clean, standardise, and manipulate text data directly within SQL queries.

---

## 4. CASE Statements

**SQL Script:** `10_case_statements.sql`

### Concepts Covered

- Conditional logic
- Categorising records
- Creating calculated columns

### Key SQL Statements

- `CASE`
- `WHEN`
- `THEN`
- `ELSE`
- `END`

### Learning Outcome

Learned how to implement business rules and conditional calculations directly within SQL queries.

---

## 5. Subqueries

**SQL Script:** `11_subqueries.sql`

### Concepts Covered

- Subqueries in `WHERE`
- Scalar subqueries
- Derived tables

### Key SQL Techniques

- Nested `SELECT`
- `IN`
- Subqueries in `FROM`

### Learning Outcome

Learned how to simplify complex queries by using nested SQL statements for filtering, aggregation, and intermediate calculations.

---

## 6. Window Functions

**SQL Script:** `12_window_functions.sql`

### Concepts Covered

- Partitioning data
- Ranking records
- Sequential numbering
- Analytical calculations

### Key SQL Functions

- `OVER()`
- `PARTITION BY`
- `ROW_NUMBER()`
- `RANK()`
- `DENSE_RANK()`

### Learning Outcome

Learned how to perform analytical calculations while preserving row-level detail, enabling advanced reporting and ranking within groups.

---

# SQL Skills Developed

Throughout these intermediate exercises, I practised:

- Joining relational tables
- Combining datasets
- Text transformation
- Conditional logic
- Nested queries
- Analytical SQL
- Ranking records
- Business-oriented query writing
- Data preparation for reporting

---

# Intermediate SQL Files

```text
07_joins.sql
08_unions.sql
09_string_functions.sql
10_case_statements.sql
11_subqueries.sql
12_window_functions.sql
```

---

# Summary

The intermediate SQL exercises extend the foundational concepts introduced in the beginner section by focusing on more practical querying and analytical techniques. These skills are widely used in data analytics, reporting, and business intelligence to combine datasets, transform data, apply business logic, and generate meaningful insights from relational databases.

The knowledge gained in this section provides the foundation for the advanced SQL topics covered in the next stage of this learning journey, including Common Table Expressions (CTEs), temporary tables, stored procedures, triggers, and events.
