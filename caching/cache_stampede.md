# Cache Stampede

Occurs when many requests hit the database after cache expiration.

## Problems

- Database overload
- Increased latency

## Solutions

- Cache locking
- Randomized TTL
- Background refresh
