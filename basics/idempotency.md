# Idempotency

## Definition

An operation is idempotent if performing it multiple times gives the same result.

---

## HTTP Methods

GET ✔

PUT ✔

DELETE ✔

POST ✘

---

## Example

Updating user name multiple times to "Archi"

Result remains same.

---

## Importance

- Retry mechanisms
- Payment systems
- Distributed systems
