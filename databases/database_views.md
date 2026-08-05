# Database Views

## What is a View?

A View is a virtual table created using an SQL query.

```sql
CREATE VIEW EmployeeView AS
SELECT name, salary
FROM Employee;
```

---

## Advantages

- Security
- Simpler queries
- Data abstraction
- Reusable SQL

---

## Updating Views

Simple views can usually be updated.

Complex views with GROUP BY, JOIN, DISTINCT, etc. are often read-only.

---

## Dropping View

```sql
DROP VIEW EmployeeView;
```
