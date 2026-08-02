# Timeouts

## Definition

Timeout is the maximum time a system waits for a response before stopping the request.

---

## Why Important?

- Prevent hanging requests
- Free resources
- Improve reliability

---

## Examples

Client ----Request----> Server

No response within timeout

↓

Request fails

---

## Best Practices

- Set reasonable timeout
- Combine with retries
- Monitor timeout errors

---

## Benefits

- Better performance
- Improved user experience
- Stable distributed systems
