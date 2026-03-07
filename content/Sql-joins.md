# SQL Joins

Joins combine rows from two or more tables based on a related column.

## Inner Join

Returns only rows that have matching values in both tables.

```sql
SELECT users.name, orders.total
FROM users
INNER JOIN orders ON users.id = orders.user_id;
```

## Left Join

Returns all rows from the left table, with matching rows from the right table (or NULL if no match).

```sql
SELECT users.name, orders.total
FROM users
LEFT JOIN orders ON users.id = orders.user_id;
```

## Right Join

The opposite of a left join — all rows from the right table are included.

## Full Outer Join

Returns all rows from both tables, filling in NULLs where there is no match.

## Parent

- [[Sql-basics]]
