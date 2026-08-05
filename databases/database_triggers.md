# Database Triggers

## What is a Trigger?

A Trigger automatically executes when an INSERT, UPDATE, or DELETE occurs.

---

## Types

- BEFORE INSERT
- AFTER INSERT
- BEFORE UPDATE
- AFTER UPDATE
- BEFORE DELETE
- AFTER DELETE

---

## Example

```sql
CREATE TRIGGER update_time
BEFORE UPDATE
ON Employee
FOR EACH ROW
SET NEW.modified = NOW();
```

---

## Uses

- Logging
- Auditing
- Validation
- Automatic updates
