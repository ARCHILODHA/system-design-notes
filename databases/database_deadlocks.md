# Database Deadlocks

## What is a Deadlock?

Occurs when two transactions wait for each other indefinitely.

---

## Example

Transaction A locks Row 1.

Transaction B locks Row 2.

A waits for Row 2.

B waits for Row 1.

Deadlock occurs.

---

## Prevention

- Lock resources in same order
- Keep transactions short
- Use timeout
- Detect and rollback one transaction
