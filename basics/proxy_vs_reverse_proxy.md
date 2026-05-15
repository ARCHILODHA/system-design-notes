# Proxy vs Reverse Proxy

Both act as intermediaries in networking.

---

# Proxy Server

Acts on behalf of client.

## Uses

- Hide client identity
- Access restrictions
- Filtering

## Flow

Client → Proxy → Internet

---

# Reverse Proxy

Acts on behalf of server.

## Uses

- Load balancing
- SSL termination
- Caching

## Flow

Client → Reverse Proxy → Server

---

# Examples

Proxy:
- VPN
- Corporate proxy

Reverse Proxy:
- Nginx
- HAProxy

---

# Comparison

| Proxy | Reverse Proxy |
|---|---|
| Protects clients | Protects servers |
| Client-side | Server-side |
