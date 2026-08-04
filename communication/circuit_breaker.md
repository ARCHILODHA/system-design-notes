# Circuit Breaker Pattern

## Definition

Circuit Breaker prevents repeated requests to a failing service.

Instead of waiting for timeout every time, requests fail immediately.

---

## States

### Closed

Everything works normally.

### Open

Requests are blocked.

### Half Open

A few requests are allowed to test recovery.

---

## Benefits

- Faster failure
- Prevent cascading failures
- Improve resilience

---

## Popular Libraries

- Resilience4j
- Hystrix

---

## Interview Question

Why use Circuit Breaker?

To stop continuously calling unhealthy services.
