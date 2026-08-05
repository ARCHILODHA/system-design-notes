# Database Execution Plan

## What is an Execution Plan?

An execution plan shows how the database executes a SQL query.

---

## It Includes

- Table scans
- Index scans
- Joins
- Sorting
- Filtering

---

## Example

```sql
EXPLAIN
SELECT *
FROM Employee
WHERE salary > 50000;
```

---

## Why Use EXPLAIN?

- Find slow queries
- Check index usage
- Reduce execution time
- Improve performance

---

## Best Practices

- Analyze expensive queries
- Create appropriate indexes
- Avoid unnecessary table scans
