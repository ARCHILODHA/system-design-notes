# Cache TTL (Time To Live)

## Definition

TTL defines how long data remains in cache before expiring.

---

## Example

```
User Profile

TTL = 30 minutes
```

After 30 minutes, cache entry is removed.

---

## Benefits

- Prevents stale data
- Automatic cache cleanup
- Better memory management

---

## Choosing TTL

- Frequently changing data → Short TTL
- Static data → Long TTL
