# Circuit Breaker Pattern

## Definition

The Circuit Breaker pattern prevents repeated requests to failing services.

## States

### Closed

Requests flow normally.

### Open

Requests are blocked.

### Half Open

A few requests are allowed to test recovery.

## Benefits

- Prevents cascading failures
- Improves resilience
- Faster recovery

## Libraries

- Resilience4j
- Hystrix
