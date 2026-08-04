# Retry Pattern

## Definition

Retry means attempting the request again after failure.

Useful for temporary network failures.

---

## Retry Strategies

- Immediate Retry
- Fixed Delay
- Exponential Backoff
- Random Jitter

---

## Example

Attempt 1 → Fail

Wait 1 sec

Attempt 2 → Fail

Wait 2 sec

Attempt 3 → Success

---

## Best Practices

- Limit retry count
- Use exponential backoff
- Avoid infinite retries

---

## Interview Question

When should retries NOT be used?

When the failure is permanent or the service is overloaded.
