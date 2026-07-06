# Enterprise WAN using GRE & NAT

A Cisco Packet Tracer project that simulates a multi-site Enterprise Wide Area Network (WAN) connecting geographically distributed branch offices through an ISP backbone. The project demonstrates enterprise-grade networking concepts including **GRE Tunneling**, **Dynamic NAT**, **Static NAT**, and **PAT (NAT Overload)**, enabling secure inter-branch communication, efficient IPv4 address utilization, and public service hosting.

---

## Project Overview

This project models a real-world enterprise WAN where multiple branch offices communicate through an ISP infrastructure. A GRE tunnel is established between the **Chennai** and **Pune** branches to provide secure logical connectivity, while Dynamic NAT, Static NAT, and PAT enable Internet access and public service hosting. The project also includes DNS resolution and HTTP web services to simulate enterprise networking environments.

---

## Network Topology

![Enterprise WAN Topology](Topology_Design.png)

---

## Features

- Multi-Site Enterprise WAN Architecture
- GRE Tunnel (Chennai ↔ Pune)
- ISP Backbone Connectivity
- Dynamic NAT
- Static NAT
- PAT (NAT Overload)
- DNS Server Configuration
- Public Web Server Hosting
- Branch Office Connectivity
- End-to-End Network Verification
- Enterprise Routing Infrastructure

---

## Network Architecture

### Branch Offices

- Chennai Branch
- Hyderabad Branch
- Engineering Branch
- Pune Branch

### ISP Network

- ISP Core Routers
- WAN Connectivity Between Sites
- GRE Tunnel Between Chennai and Pune

### Network Services

- GRE Tunnel
- Dynamic NAT
- Static NAT
- PAT (NAT Overload)
- DNS
- HTTP Web Hosting

---

## NAT & GRE Implementation

| Technology | Purpose |
|------------|---------|
| GRE Tunnel | Provides secure logical connectivity between Chennai and Pune branches |
| Dynamic NAT | Maps private IP addresses to a pool of public IP addresses |
| Static NAT | Maps internal servers to fixed public IP addresses |
| PAT (NAT Overload) | Allows multiple devices to share a single public IP address |

---

## Technologies Used

- Cisco Packet Tracer
- Cisco IOS CLI
- IPv4 Addressing
- GRE Tunnel
- Dynamic NAT
- Static NAT
- PAT (NAT Overload)
- WAN Routing
- DNS
- HTTP
- Enterprise Networking

---

## Project Files

| File | Description |
|------|-------------|
| `Project_GRE_VPN.pkt` | Cisco Packet Tracer project file |
| `Topology_Design.png` | Enterprise WAN topology |
| `Output(1).png` | GRE tunnel and website connectivity verification |
| `README.md` | Project documentation |

---

## Verification

The project successfully demonstrates:

- ✅ GRE Tunnel Connectivity
- ✅ Dynamic NAT Translation
- ✅ Static NAT Configuration
- ✅ PAT (NAT Overload)
- ✅ Branch-to-Branch Connectivity
- ✅ Internet Access
- ✅ DNS Name Resolution
- ✅ Public Website Accessibility
- ✅ End-to-End WAN Communication

### Enterprise WAN Topology

![Enterprise WAN Topology](Topology_Design.png)

### GRE Tunnel & Website Verification

![GRE Tunnel Verification](Output(1).png)

---

## Real-World Applications

This architecture is similar to enterprise networks deployed in:

- Corporate Organizations
- Banking Networks
- Educational Institutions
- Government Agencies
- IT Service Companies
- Multi-Branch Enterprises

---

## Learning Outcomes

- Enterprise WAN Design
- GRE Tunnel Configuration
- Dynamic NAT Configuration
- Static NAT Configuration
- PAT (NAT Overload)
- WAN Routing
- DNS Configuration
- HTTP Server Configuration
- Cisco IOS CLI
- Enterprise Network Troubleshooting

---

## Prerequisites

- Cisco Packet Tracer 8.x or later

### Basic Knowledge Required

- Computer Networks
- IPv4 Addressing
- Routing
- Cisco IOS CLI
- NAT Concepts
- GRE Tunneling

---

## How to Run

1. Clone the repository.

```bash
git clone https://github.com/praveen272004/Enterprise-WAN-using-GRE-NAT.git
```

2. Open `Project_GRE_VPN.pkt` using Cisco Packet Tracer.

3. Run the project in **Realtime** or **Simulation** mode.

4. Verify:

   - GRE Tunnel Connectivity
   - Dynamic NAT Translation
   - Static NAT Mappings
   - PAT (NAT Overload)
   - Branch-to-Branch Communication
   - DNS Name Resolution
   - Website Accessibility

---

## Case Study

A growing enterprise with branch offices in **Chennai, Hyderabad, Engineering, and Pune** requires secure communication across geographically distributed locations while providing Internet connectivity and public-facing services. This project simulates an ISP-connected WAN where a **GRE tunnel securely connects the Chennai and Pune branches**, Dynamic NAT and PAT enable Internet access for internal users, and Static NAT publishes enterprise web and DNS servers. The solution demonstrates scalable WAN architecture, secure inter-branch communication, efficient IPv4 address utilization, and reliable enterprise networking.

---

## Author

**Praveen M**

---

⭐ If you found this project useful, consider giving it a **Star** on GitHub!
