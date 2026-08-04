# Message Ordering

## Definition

Message Ordering ensures messages are processed in the same order they were produced.

---

## Why Important?

- Banking
- Chat applications
- Stock trading
- Event processing

---

## Example

Deposit ₹100

Withdraw ₹50

Correct Balance = ₹50

If order changes:

Withdraw ₹50

Deposit ₹100

Incorrect result may occur.

---

## Challenges

- Multiple producers
- Parallel consumers
- Network delays

---

## Solutions

- Single partition
- Sequence numbers
- FIFO queues

---

## Interview Question

Does Kafka guarantee ordering?

Yes, within a partition.
