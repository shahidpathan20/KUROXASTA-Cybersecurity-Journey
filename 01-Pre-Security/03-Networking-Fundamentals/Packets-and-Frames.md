# Packets and Frames

## Packets — Layer 3
An IP packet carries information used to move data between networks. Its header includes source and destination IP addresses and fields such as TTL (IPv4) or hop limit (IPv6).

## Frames — Layer 2
An Ethernet frame carries data over a local link and includes source and destination MAC addresses.

Network-layer packets are encapsulated inside link-layer frames for delivery across a link. Routers typically replace the link-layer frame when forwarding a packet to the next link.

| Feature | Packet | Frame |
|---|---|---|
| Common layer | Layer 3 — Network | Layer 2 — Data Link |
| Addressing | IP addresses | MAC addresses on Ethernet |
| Role | Delivery between networks | Delivery over a local link |

[Back to Networking Fundamentals](README.md)