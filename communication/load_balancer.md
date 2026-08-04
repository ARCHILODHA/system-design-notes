# Load Balancer

## Definition

A Load Balancer distributes incoming requests among multiple servers.

Purpose:
- Improve availability
- Increase scalability
- Prevent overload

---

## Types

### Layer 4

Works on TCP/UDP.

Fast but less intelligent.

Examples:
- Nginx Stream
- AWS NLB

---

### Layer 7

Works on HTTP/HTTPS.

Can route based on URL, cookies, headers.

Examples:
- HAProxy
- Nginx
- AWS ALB

---

## Algorithms

- Round Robin
- Least Connections
- IP Hash
- Weighted Round Robin

---

## Benefits

- High availability
- Better performance
- Scalability
- Fault tolerance

---

## Interview Question

Why use Load Balancer?

To evenly distribute traffic and prevent one server from becoming overloaded.
