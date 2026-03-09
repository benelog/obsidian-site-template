---
tags:
  - sql
  - database
---
# SQL Basics

SQL (Structured Query Language) is the standard language for interacting with relational databases like PostgreSQL, MySQL, and SQLite.

## Core statements

- `SELECT` - Query data from tables
- `INSERT` - Add new rows
- `UPDATE` - Modify existing rows
- `DELETE` - Remove rows

## Example

```sql
SELECT name, email
FROM users
WHERE active = true
ORDER BY name;
```

## Topics

- [[Sql-joins]] - Combining data from multiple tables

## Parent

- [[Databases]]
