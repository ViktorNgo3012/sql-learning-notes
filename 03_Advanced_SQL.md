# Advanced SQL Notes

## Overview

This document summarises the advanced SQL concepts covered during the final stage of my SQL learning journey using MySQL.

Building on the beginner and intermediate topics, these exercises introduce more advanced database programming techniques that improve query organisation, automate repetitive tasks, and increase the reusability of SQL code.

The examples use the Parks and Recreation sample database and demonstrate practical SQL features that are commonly encountered in database development, reporting systems, and data engineering workflows.

---

## Learning Objectives

After completing this section, I was able to:

- Organise complex SQL queries using Common Table Expressions (CTEs).
- Create and use temporary tables for intermediate data processing.
- Develop reusable SQL logic using stored procedures.
- Understand how triggers automatically respond to database events.
- Learn how scheduled events can automate recurring database tasks.
- Improve SQL readability, maintainability, and modularity.

---

# Advanced SQL Topics

## 1. Common Table Expressions (CTEs)

**SQL Script:** `13_ctes.sql`

### Concepts Covered

- Creating Common Table Expressions using `WITH`
- Referencing CTEs within a query
- Simplifying complex SQL statements
- Improving query readability

### Why It Matters

CTEs make SQL queries easier to understand and maintain by breaking large queries into logical steps. They are widely used in reporting, analytics, and data transformation.

---

## 2. Temporary Tables

**SQL Script:** `14_temporary_tables.sql`

### Concepts Covered

- Creating temporary tables
- Inserting intermediate query results
- Reusing temporary datasets
- Automatically removing temporary tables after the session ends

### Why It Matters

Temporary tables are useful when processing data through multiple stages without permanently storing intermediate results. They are commonly used in ETL pipelines, reporting, and data preparation.

---

## 3. Stored Procedures

**SQL Script:** `15_stored_procedures.sql`

### Concepts Covered

- Creating stored procedures
- Executing stored procedures
- Using parameters
- Applying custom delimiters
- Encapsulating reusable SQL logic

### Why It Matters

Stored procedures improve code reusability and simplify repetitive database operations. They are frequently used in enterprise database systems to centralise business logic.

---

## 4. Triggers and Events

**SQL Script:** `16_triggers_and_events.sql`

### Concepts Covered

- Creating database triggers
- Automatically responding to INSERT events
- Creating scheduled database events
- Automating repetitive database tasks

### Why It Matters

Triggers and events allow databases to automatically perform actions when predefined conditions occur. These features support data integrity and reduce manual maintenance tasks.

---

# Advanced SQL Skills Developed

During this stage, I practised:

- Common Table Expressions (CTEs)
- Temporary Tables
- Stored Procedures
- SQL Delimiters
- Stored Procedure Parameters
- Database Triggers
- Scheduled Events
- Modular SQL Design
- Database Automation
- Query Organisation

---

# Files Included

```
03_Advanced_SQL.md

13_ctes.sql
14_temporary_tables.sql
15_stored_procedures.sql
16_triggers_and_events.sql
```

---

# Key Takeaways

This stage extended my SQL knowledge beyond writing queries by introducing database programming concepts and automation features.

Through these exercises, I learned how to structure complex SQL using CTEs, temporarily store intermediate results, encapsulate reusable logic with stored procedures, and automate database behaviour using triggers and scheduled events.

Together with the beginner and intermediate sections, these topics provide a solid foundation in SQL for data analysis and prepare me for more advanced work in data engineering, business intelligence, and database development.

---

# Next Steps

To continue developing my SQL skills, I plan to:

- Apply advanced SQL techniques to larger real-world datasets.
- Practise query optimisation and performance tuning.
- Explore indexing strategies and execution plans.
- Integrate SQL with Python for data analysis workflows.
- Build end-to-end SQL portfolio projects using business datasets.
