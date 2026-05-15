# Single Point of Failure (SPOF)

A component whose failure stops the entire system.

---

# Examples

- One database server
- One load balancer
- Single internet connection

---

# Problems

- Downtime
- Data loss
- Poor reliability

---

# Avoiding SPOF

## Redundancy

Use backup servers.

## Replication

Maintain multiple database copies.

## Load Balancing

Distribute traffic across servers.

## Failover

Automatically switch to backup systems.

---

# Real Example

If one payment server crashes:
- Entire payment system fails

Solution:
- Multiple payment servers

---

# Goal

Build highly available systems without dependency on one component.
