# SSH-CONFIGURATION-ON-A-CISCO-ROUTER.
# Cisco Packet Tracer — Networking Lab Documentation Project

A personal documentation portfolio based on hands-on CCNA networking studies using Cisco Packet Tracer. Each lab is translated into a professional Word document covering topology, configuration, verification, and real-world context.

---

## Documents

### 1. Basic Network Configuration
**File:** `Cisco_PacketTracer_BasicNetwork_Documentation.docx`

Covers building a two-LAN topology from scratch and establishing communication between devices on different network segments.

- **Topology:** 4 PCs · 2 Switches · 1 Router
- **Networks:** 192.168.1.0/24 and 192.168.2.0/24
- **Key topics:** IP addressing, subnet masks, default gateways, router interface configuration, Simple PDU testing, ping verification
- **CLI commands:** `interface`, `ip address`, `no shutdown`, `show ip interface brief`, `show ip route`

---

### 2. Configuring SSH on a Cisco Router
**File:** `Configuring_SSH_Cisco_Router.docx`

Covers replacing insecure Telnet with SSH Version 2 for encrypted remote router management, framed within a real-world network security scenario.

- **Scenario:** SecureBank Financial Services — branch router security audit remediation
- **Key topics:** SSH vs Telnet, RSA key generation, SSHv2 enforcement, VTY line hardening, brute-force protection, compliance (PCI-DSS, ISO 27001, NIST, SOC 2)
- **CLI commands:** `crypto key generate rsa`, `ip ssh version 2`, `transport input ssh`, `login local`, `show ip ssh`, `show ssh`

---

## Tools Used
- Cisco Packet Tracer (Cisco Networking Academy)
- Cisco IOS CLI

## Study Reference
- https://youtu.be/uEb3Y--jAsY?si=qOVKNDTviWuZZBzh
- Cisco Networking Academy curriculum
