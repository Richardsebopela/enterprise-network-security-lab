# Enterprise Network Security Lab

## Project Overview

This project demonstrates the design, implementation, and testing of a secure enterprise network using Cisco Packet Tracer.

The network simulates three departments: IT, Human Resources (HR), and Finance. It uses network segmentation, routing, access control, firewall protection, and Network Address Translation (NAT).

## Network Architecture

**Network path:**

Internet Server → ISP Router → Cisco ASA Firewall → Enterprise Router → Switch → Department PCs

## Technologies and Security Features

- **VLANs:** VLAN 10 (IT), VLAN 20 (HR), VLAN 30 (Finance)
- **Inter-VLAN Routing:** Router-on-a-stick using IEEE 802.1Q
- **Access Control Lists:** Restricts HR access to the Finance network
- **Cisco ASA Firewall:** Separates internal and external networks
- **NAT/PAT:** Translates internal addresses for external communication
- **Switch Port Security:** Sticky MAC address learning and restricted violations
- **Static Routing:** Provides connectivity between network segments

## Security Testing

The following tests were performed in Cisco Packet Tracer:

| Test | Result |
|---|---|
| IT to HR connectivity | Successful |
| IT to Finance connectivity | Successful |
| HR to Finance restriction | Blocked as intended |
| IT to simulated Internet Server | Successful |
| Switch port security configuration | Verified |
| Firewall NAT configuration | Verified |

## Tools Used

- Cisco Packet Tracer
- Cisco IOS CLI
- Cisco ASA Firewall
- Network troubleshooting commands

## Skills Demonstrated

- Enterprise network design
- Network segmentation
- Router and switch configuration
- Firewall administration
- Network access control
- Connectivity testing and troubleshooting
- Security documentation

## Project Files

- `Enterprise_Network_Security_Richard.pkt` — Cisco Packet Tracer simulation
- Project report and network screenshots — supporting documentation to be uploaded

## Author

Cybersecurity and Networking Student

*This project is a simulated enterprise security lab created for practical learning and portfolio development.*
