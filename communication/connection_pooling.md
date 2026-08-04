# Connection Pooling

## Definition

Connection Pooling keeps reusable connections ready instead of creating new ones every request.

---

## Benefits

- Faster response
- Lower latency
- Less CPU usage

---

## Example

Without Pool

Request
↓

Create Connection
↓

Query

↓

Close

With Pool

Request

↓

Reuse Existing Connection

↓

Return to Pool

---

## Popular Pools

- HikariCP
- C3P0
- Apache DBCP

---

## Interview Question

Why use Connection Pooling?

Creating connections repeatedly is expensive.
