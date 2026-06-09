# Long Polling

Client sends a request and waits until data becomes available.

## Flow
1. Client requests update
2. Server holds request
3. Server responds when data arrives
4. Client reconnects

## Advantages
- Near real-time

## Disadvantages
- Connection overhead

## Use Cases
- Notifications
- Live dashboards
