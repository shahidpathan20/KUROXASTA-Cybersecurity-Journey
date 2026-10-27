# Introduction to LAN

A **LAN (Local Area Network)** connects devices within a limited area and can support sharing data, printers, and other resources.

## Network topologies
- **Star:** devices connect to a central switch or hub. Easy to manage and expand, but failure of the central device can disrupt connections.
- **Bus:** devices share a main backbone cable. It can be inexpensive but is harder to troubleshoot and a backbone failure can disrupt the network.
- **Ring:** devices form a loop. A simple ring can be affected by a device or cable failure.

## Switching and routing
A **switch** connects devices in a LAN and forwards frames using MAC-address information. A **router** connects IP networks and forwards packets between them.

## Subnetting
Subnetting divides a larger IP network into smaller networks.

- **Network address:** identifies a subnet, for example 192.168.1.0/24.
- **Host addresses:** addresses used by device interfaces.
- **Default gateway:** router address used to reach destinations outside the local subnet.

## ARP and DHCP
- **ARP:** in IPv4 local networks, helps find the MAC address associated with a local IPv4 address.
- **DHCP:** can automatically provide an IP address, subnet mask/prefix, default gateway, and DNS servers.

[Back to Networking Fundamentals](README.md)