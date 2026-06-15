FortiGate Enterprise Security Lab

Overview

Designed and implemented a highly available multi-branch enterprise network infrastructure using FortiGate firewalls. The project simulates a real-world enterprise environment with centralized security, dynamic routing, secure branch connectivity, SD-WAN optimization, automated operations, and disaster recovery validation.

---

Architecture

Headquarters (HQ)

- FortiGate HA Cluster (Active-Active)
- Internal LAN: 192.168.20.0/24
- Windows Server for LDAP authentication and centralized configuration backup storage
- SSL VPN Portal for remote access

Cairo Branch

- Internal LAN: 172.16.10.0/24
- Site-to-Site IPsec VPN connectivity with HQ

Minya Branch

- Internal LANs: 10.10.15.0/24 and 10.10.20.0/24
- Redundant VPN connectivity to HQ and Cairo Branch
- SD-WAN path selection based on SLA monitoring

---

Implemented Technologies

Network Infrastructure

- High Availability (Active-Active)
- OSPF Dynamic Routing
- SD-WAN
- SLA-Based Path Selection
- Site-to-Site IPsec VPN
- SSL VPN (Portal)

Security Controls

- Intrusion Prevention System (IPS)
- Application Control 
- Web Filtering
- Deep SSL Inspection
- VIP / DNAT Services
- Administrative Access Hardening
- Trusted Hosts

Identity & Access Management

- LDAP Authentication Integration

Automation & Monitoring

- Automated Configuration Backup every 4 hours (for each branch) 
- Centralized Backup Repository on Windows Server (For each branch)
- Email Alerting for Critical Events (For each branch)
- HA Failover Monitoring (HQ Branch)

Performance Optimization

- Traffic Shaping
- Bandwidth Management

---

Validation Scenarios

✔ HA Failover Testing

✔ VPN Redundancy Testing

✔ SD-WAN Path Switching Validation

✔ LDAP User Authentication

✔ FFSO

✔ SSL VPN Remote Access (Portal)

✔ Automated Backup Verification

✔ Security Profile Enforcement

✔ Email Alert Generation

---

Key Achievements

- Built a resilient enterprise-grade network across multiple sites.
- Implemented layered security controls using FortiGate Security Profiles.
- Achieved secure branch-to-branch and branch-to-HQ communication through encrypted VPN tunnels.
- Automated backup and monitoring operations to improve operational efficiency.
- Validated failover and redundancy mechanisms to ensure business continuity.

---

Technologies Used

- FortiGate
- FortiOS 7.6
- OSPF
- SD-WAN
- IPsec VPN
- SSL VPN
- LDAP
- Windows Server
- IPS
- Deep SSL Inspection
- Traffic Shaping

---

Screenshots & Demonstrations

- Network Topology
- HA Failover Demonstration
- SD-WAN Path Switching
- SSL VPN Connectivity
- Email Alerting
- Automated Backup Process
