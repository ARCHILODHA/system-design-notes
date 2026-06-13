# Load Balancer

## What is a Load Balancer?

A Load Balancer distributes incoming requests across multiple servers to prevent overload and improve availability.

## Benefits

- High Availability
- Scalability
- Fault Tolerance
- Better Performance

## Types

### Layer 4 Load Balancer
Routes based on IP and Port.

### Layer 7 Load Balancer
Routes based on HTTP headers, URL, cookies, etc.

## Algorithms

- Round Robin
- Weighted Round Robin
- Least Connections
- IP Hash

## Example

User Requests
       |
       V
+----------------+
| Load Balancer  |
+----------------+
   /     |     \
  V      V      V
Server1 Server2 Server3

## Popular Tools

- Nginx
- HAProxy
- AWS ELB
