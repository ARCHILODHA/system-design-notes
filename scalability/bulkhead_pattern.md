# Bulkhead Pattern

## Definition

The Bulkhead Pattern isolates failures by separating system resources.

## Benefits

- Prevents one failure from affecting the whole system
- Better reliability
- Easier scaling

## Example

Separate thread pools for:

- Payment Service
- Notification Service
- User Service
