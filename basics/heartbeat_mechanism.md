# Heartbeat Mechanism

## Definition

Heartbeat is a periodic signal sent by a service to indicate it is alive.

---

## Working

Server → Heartbeat → Registry

No heartbeat for a long time means service failure.

---

## Applications

- Distributed systems
- Cluster management
- Database replication
- Leader election

---

## Advantages

- Fast failure detection
- High reliability
