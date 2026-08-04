# Distributed Lock

## Definition

Distributed Lock ensures only one server accesses a shared resource at a time.

---

## Example

Inventory Update

Server A ✔

Server B waits

---

## Implementations

- Redis
- ZooKeeper
- etcd

---

## Advantages

- Prevent race conditions
- Ensure consistency

---

## Interview Question

When do we need Distributed Lock?

When multiple servers update the same data simultaneously.
