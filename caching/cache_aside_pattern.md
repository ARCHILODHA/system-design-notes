# Cache Aside Pattern

Cache Aside is one of the most widely used caching patterns.

## Workflow

1. Application checks cache
2. If cache miss occurs, fetch data from database
3. Store data in cache
4. Return response

## Advantages

- Easy to implement
- Reduces database load

## Disadvantages

- Cache misses increase latency
