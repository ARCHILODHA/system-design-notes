# Service Discovery

## What is Service Discovery?

Service Discovery is a mechanism that enables services in a distributed system to automatically locate and communicate with each other.

Instead of hardcoding IP addresses, services register themselves with a registry.

---

## Why is it Needed?

- Dynamic infrastructure
- Containers restart frequently
- Auto scaling
- High availability

---

## Components

- Service Provider
- Service Registry
- Service Consumer

---

## Types

### Client-Side Discovery

Client queries registry directly.

Example:
Netflix Eureka

---

### Server-Side Discovery

Load Balancer queries registry.

Example:
AWS ELB
Kubernetes Services

---

## Popular Tools

- Eureka
- Consul
- Zookeeper
- Kubernetes DNS

---

## Advantages

- Fault tolerance
- Automatic scaling
- Dynamic routing
- Easier maintenance

---

## Disadvantages

- Extra infrastructure
- Registry becomes critical component
