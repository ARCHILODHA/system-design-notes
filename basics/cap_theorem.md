# CAP Theorem

CAP Theorem states that a distributed system can only guarantee two out of the following three properties:

1. Consistency
2. Availability
3. Partition Tolerance

---

## 1. Consistency

Every user gets the latest updated data.

Example:
If one user updates a profile, all users immediately see the updated profile.

---

## 2. Availability

Every request receives a response even if some servers fail.

Example:
The system always responds to users.

---

## 3. Partition Tolerance

The system continues working even if communication between servers breaks.

Example:
Network failure between data centers.

---

# CAP Combinations

## CP System

Consistency + Partition Tolerance

- Prioritizes correct data
- May sacrifice availability

Examples:
- MongoDB
- HBase

---

## AP System

Availability + Partition Tolerance

- System always responds
- Data may become temporarily inconsistent

Examples:
- Cassandra
- DynamoDB

---

## CA System

Consistency + Availability

- Works only when no partition occurs
- Rare in distributed systems

Examples:
- Traditional SQL databases

---

# Real World Importance

Modern distributed systems usually choose:

- CP or AP
- Because network partitions are unavoidable

---

# Summary

| Property | Meaning |
|---|---|
| Consistency | Same data everywhere |
| Availability | System always responds |
| Partition Tolerance | System survives network failures |
