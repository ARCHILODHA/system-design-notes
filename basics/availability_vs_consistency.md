# Availability vs Consistency

Distributed systems often balance consistency and availability.

---

# Consistency

All users see the same latest data.

## Example

Bank balance updates instantly everywhere.

## Advantages

- Accurate data
- Reliable transactions

## Disadvantages

- Higher latency
- Possible downtime during failures

---

# Availability

The system always responds.

## Example

Social media feed loads even during server issues.

## Advantages

- Better user experience
- Faster responses

## Disadvantages

- Temporary stale data

---

# Tradeoff

In distributed systems:

- Strong consistency may reduce availability
- High availability may allow stale data

---

# Real Examples

| System | Preference |
|---|---|
| Banking | Consistency |
| Instagram Feed | Availability |
| WhatsApp Messages | Balanced |

---

# Conclusion

Choose based on application requirements.
