# Query Optimization

## What is Query Optimization?

Improving SQL queries for faster execution.

---

## Techniques

- Use indexes
- Avoid SELECT *
- Filter early
- Use LIMIT
- Normalize tables
- Analyze execution plans

---

## Bad Query

```sql
SELECT *
FROM Employee;
```

---

## Better Query

```sql
SELECT id, name
FROM Employee
WHERE department='IT';
```

---

## Benefits

- Faster execution
- Lower CPU usage
- Better scalability
