# Secure Three-Tier Enterprise Network Architecture – Cisco Packet Tracer Simulation
Cisco Packet Tracer simulation of a secure three-tier enterprise network with BGP, EIGRP, VPN, ACLs, and more.

## Project By:
**Sandipa Pun**  

## Overview
This project demonstrates the design and simulation of a **secure and scalable three-tier network architecture** using Cisco Packet Tracer. The architecture integrates **access, distribution, and core layers**, connecting a headquarters and branch office with a focus on high availability, security, and redundancy.

## Architecture Components
- **Access Layer**: 6 Layer 2 switches with port security, VLANs, BPDU Guard, and PortFast.
- **Distribution Layer**: 4 multilayer switches with HSRP-based load balancing and inter-VLAN routing.
- **Core Layer**: Central services including DNS, DHCP, Web Server, SMTP, Syslog, SNMP, AAA, and NTP.

## Network Features
- **VLANs and VTP** for segmentation and centralized management.
- **DHCP** and relay agent for IP distribution.
- **Routing Protocols**:  
  - EIGRP (Headquarter)  
  - OSPF (Branch)  
  - BGP (Public ISP Routing)
- **Security Features**:  
  - Access Control Lists (ACLs)  
  - Network Address Translation (NAT)  
  - VPN for secure HQ-Branch communication  
  - AAA for user authentication and authorization
- **Redundancy and Load Balancing**:
  - HSRP-based gateway redundancy
  - EtherChannel (LACP) for link aggregation
- **Wireless Support**: WLC-managed wireless access with DHCP support
- **Firewall Implementation**: Traffic filtering between internal and public networks

## Tools Used
- Cisco Packet Tracer

## Test Scenarios
- HQ ↔ Branch PC communication over VPN
- DNS resolution (e.g., `facebook.com`)
- Email exchange using SMTP
- Web page loading from internal web server
- Log collection via Syslog and SNMP hostname updates

## Conclusion
This project showcases how layered architectures combined with modern routing protocols and security best practices can create resilient enterprise networks. The design ensures **confidentiality**, **availability**, and **integrity** while supporting future scalability.


