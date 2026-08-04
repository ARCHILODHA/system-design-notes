# Backpressure

## Definition

Backpressure controls data flow when the receiver cannot process data fast enough.

---

## Why Needed?

Without backpressure:
- Memory overflow
- Slow consumers
- System crash

---

## Solutions

- Queue
- Rate limiting
- Buffering
- Drop requests

---

## Example

Producer → 1000 msgs/sec

Consumer → 200 msgs/sec

Backpressure slows producer.

---

## Interview Question

Why is backpressure important?

It prevents overwhelming downstream services.
