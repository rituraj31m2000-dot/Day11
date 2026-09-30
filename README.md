# Day 11 – Networking Fundamentals

**Internship:** Veda Technology – Cyber Security Track
**Intern:** Ritu Raj
**Level:** 1 | **Task:** 11

## Objective
Build the networking knowledge required for cybersecurity by studying IP addresses, MAC addresses, ports, protocols and network devices.

## Tools Used
- Cisco Packet Tracer
- Web browser

## What I Learned

### IP Address
A logical address that identifies a device on a network. IPv4 (e.g. 192.168.1.10) is 32-bit; IPv6 is 128-bit.

### MAC Address
A unique 48-bit hardware address assigned to a network interface card (e.g. 00:1A:2B:3C:4D:5E). It works at Layer 2.

### Ports
Logical endpoints for services on a device.

| Port | Service |
|------|---------|
| 22 | SSH |
| 53 | DNS |
| 80 | HTTP |
| 443 | HTTPS |

### Protocols
- **TCP:** reliable, connection-oriented
- **UDP:** fast, connectionless
- **HTTP/HTTPS:** web communication
- **DNS:** domain name to IP resolution
- **DHCP:** automatic IP assignment
- **ICMP:** diagnostics (ping)

### Network Devices
- **Router:** connects different networks and routes packets
- **Switch:** connects devices within a LAN using MAC addresses
- **Firewall:** filters traffic based on security rules

## Practical (Cisco Packet Tracer)
1. Placed 1 switch and 2 PCs
2. Connected them using copper straight-through cables
3. Assigned static IPs (192.168.1.10 and 192.168.1.11, mask 255.255.255.0)
4. Tested connectivity with `ping`

Screenshots are in the `/screenshots` folder.

## Security Relevance
Attacks such as port scanning, ARP/MAC spoofing and packet sniffing exploit networking basics. Understanding them is the first step in defending against them.

## Outcome
Understood the core networking concepts and built and verified a basic network in Packet Tracer.

