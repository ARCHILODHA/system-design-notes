# Polling vs Webhooks

## Polling
Client repeatedly asks server for updates.

### Pros
- Simple implementation

### Cons
- Wasted requests
- Increased latency

## Webhooks
Server notifies client when an event occurs.

### Pros
- Efficient
- Real-time

### Cons
- Requires public endpoint

## Use Cases
- Polling: Small internal systems
- Webhooks: Payment notifications
