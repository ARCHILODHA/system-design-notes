# Idempotency

An operation is idempotent if multiple executions produce the same result.

## Example

Creating an order:
- Use an Idempotency Key
- Duplicate requests return the same response

## Benefits
- Prevents duplicate processing
- Improves reliability

## Common Usage
- Payment systems
- Order creation APIs
