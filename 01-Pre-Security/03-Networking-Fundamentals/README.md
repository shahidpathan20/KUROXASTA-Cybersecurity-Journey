# Networking Fundamentals

## 1. What Is Networking?
Networking connects computers and devices so they can communicate and share data.

### Main purposes
- Share information and files.
- Share an internet connection.
- Communicate between devices.

### Types of networks
- **LAN (Local Area Network):** limited area, such as a home, school, or office.
- **WAN (Wide Area Network):** connects networks across larger geographic areas; the internet is a familiar example.

### Common devices
- **Router:** connects different networks and forwards traffic.
- **Switch:** connects devices within a LAN.
- **Modem:** connects a network to an ISP using the relevant access technology.

## 2. Introduction to LAN
A **LAN** connects devices within a limited area and can support sharing data, printers, and other resources.

### Network topologies
- **Star:** devices connect to a central switch or hub. Easy to manage and expand, but failure of the central device can disrupt connections.
- **Bus:** devices share a main backbone cable. It can be inexpensive but is harder to troubleshoot and a backbone failure can disrupt the network.
- **Ring:** devices form a loop. Traffic follows the ring; a simple ring can be affected by a device or cable failure.

### Switching and routing
A **switch** connects devices in a LAN and forwards frames using MAC-address information. A **router** connects IP networks and forwards packets between them. Routing is the process of choosing paths for packets.

### Subnetting
Subnetting divides a larger IP network into smaller networks, helping organization, address management, and traffic control.

- **Network address:** identifies a subnet, for example, 192.168.1.0/24 in a common IPv4 example.
- **Host addresses:** addresses used by device interfaces on the subnet.
- **Default gateway:** router address used to reach destinations outside the local subnet; often 192.168.1.1 on home networks.

### ARP and DHCP
- **ARP (Address Resolution Protocol):** in IPv4 local networks, helps find the MAC address associated with a local IPv4 address.
- **DHCP (Dynamic Host Configuration Protocol):** can automatically provide an IP address, subnet mask/prefix, default gateway, and DNS servers.

Typical flow: a device joins the network; DHCP provides configuration; ARP may resolve local addresses; switches forward local frames; routers forward packets to other networks.

## 3. OSI Model
The **Open Systems Interconnection (OSI) model** is a seven-layer framework for understanding network communication.

Encapsulation means protocol information is added as data moves down the layers so it can be transported and delivered. At the receiving end, that information is processed as data moves back up the layers.

| Layer | Name | Main idea |
|---:|---|---|
| 7 | Application | Network services used by applications, such as web and email protocols. |
| 6 | Presentation | Data representation, encoding, compression, and encryption concepts. |
| 5 | Session | Establishes, manages, and ends communication sessions. |
| 4 | Transport | End-to-end transport; TCP provides reliable ordered delivery, while UDP provides datagrams without the same guarantees. |
| 3 | Network | Logical addressing and routing; IP operates here. |
| 2 | Data Link | Local-link communication; Ethernet frames and MAC addresses are examples. |
| 1 | Physical | Transmits bits as electrical, optical, or radio signals. |

Remember bottom to top: **Physical, Data Link, Network, Transport, Session, Presentation, Application**.

## 4. Packets and Frames

### Packets — Layer 3
An IP packet carries information used to move data between networks. Its header includes source and destination IP addresses and fields such as TTL (IPv4) or hop limit (IPv6).

### Frames — Layer 2
An Ethernet frame carries data over a local link and includes source and destination MAC addresses.

Network-layer packets are encapsulated inside link-layer frames for delivery across a link. Routers typically replace the link-layer frame when forwarding a packet to the next link.

| Feature | Packet | Frame |
|---|---|---|
| Common layer | Layer 3 — Network | Layer 2 — Data Link |
| Addressing | IP addresses | MAC addresses on Ethernet |
| Role | Delivery between networks | Delivery over a local link |

## 5. Extending Your Network

### Port forwarding
Port forwarding is a router configuration that directs incoming traffic arriving at a public IP address and port to a selected device and port inside a private network. Exposing a service to the internet introduces risk, so only necessary ports should be opened and the service should be secured.

### Firewalls
A **firewall** monitors and controls network traffic according to rules.

- **Stateless firewall:** evaluates packets individually against rules.
- **Stateful firewall:** tracks connection state and uses context about ongoing connections when making decisions.

**Quick revision:** port forwarding directs incoming traffic to an internal service; firewalls control traffic; stateless filtering examines packets individually; stateful filtering considers connection state.
