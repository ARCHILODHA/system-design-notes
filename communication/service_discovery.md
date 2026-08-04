# Service Discovery

## What is Service Discovery?

Service Discovery is the process of automatically detecting services available in a distributed system.

Instead of hardcoding server IP addresses, applications ask a service registry where a service is running.

---

## Why is it needed?

- Dynamic scaling
- Fault tolerance
- Load balancing
- Cloud-native deployments

---

## Types

### Client-side Discovery

Client asks registry for available instances.

Examples:
- Netflix Eureka
- Consul

Advantages:
- Faster
- More control

Disadvantages:
- Client becomes complex

---

### Server-side Discovery

Client sends request to load balancer.

Examples:
- AWS ELB
- Kubernetes Service

Advantages:
- Simple client

Disadvantages:
- Extra network hop

---

## Workflow

Client
↓
Service Registry
↓
Available Servers
↓
Client selects server
↓
Request sent

---

## Popular Tools

- Eureka
- Consul
- ZooKeeper
- Kubernetes DNS

---

## Interview Question

Why is Service Discovery important in Microservices?

Because service instances change frequently, and clients need a way to find them dynamically.
