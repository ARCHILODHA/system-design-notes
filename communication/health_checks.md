# Health Checks

## Definition

Health checks verify whether a service is healthy.

---

## Types

### Liveness Probe

Checks if application is alive.

### Readiness Probe

Checks if application is ready to receive traffic.

---

## HTTP Example

GET /health

Response:

200 OK

---

## Benefits

- Detect failures
- Automatic recovery
- Better reliability

---

## Used In

- Kubernetes
- Docker
- Cloud platforms

---

## Interview Question

Difference between Liveness and Readiness?

Liveness checks if app is running.

Readiness checks if app can accept requests.
