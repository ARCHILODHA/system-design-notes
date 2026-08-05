# Stored Procedures

## What is a Stored Procedure?

A stored procedure is a collection of SQL statements stored inside the database.

---

## Syntax

```sql
CREATE PROCEDURE GetEmployees()
BEGIN
SELECT * FROM Employee;
END;
```

---

## Calling Procedure

```sql
CALL GetEmployees();
```

---

## Advantages

- Faster execution
- Code reuse
- Better security
- Easier maintenance

---

## Disadvantages

- Database dependent
- Debugging can be difficult
