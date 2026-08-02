# Quorum

## Definition

Quorum is the minimum number of nodes required to perform an operation safely.

Formula:

```
Read Quorum + Write Quorum > Total Replicas
```

---

## Benefits

- Consistency
- Fault tolerance

---

## Example

Replication Factor = 3

Read = 2

Write = 2

2 + 2 > 3

Data remains consistent.
