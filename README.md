# smart-office-network-simulation
A secure, VLAN-based smart office network simulation using Cisco Packet Tracer, implementing segmented departments, RIP &amp; OSPF routing, wireless access, and firewall ACLs.
# Smart Office Network Simulation – Cisco Packet Tracer

##  Objective

Simulate a secure, scalable smart office network using Cisco Packet Tracer. The design reflects real-world departmental segmentation, basic routing diversity (RIP, OSPF), and layered security across wired and wireless zones.

---

##  Network Topology

| Block       | Description                       | Devices     |
|-------------|-----------------------------------|-------------|
| A           | Admin Department (Planned 802.1X) | 3 PCs       |
| B           | HR Department (VLAN 20)           | 3 PCs       |
| C           | R&D Department (VLAN 30)          | 3 PCs       |
| D           | Server Room (Web, DNS, Mail)      | 3 Servers   |
| E           | Wi-Fi Zone (WPA2-Secured)         | 2 Laptops   |

**Total:** 9 PCs, 2 Laptops, 3 Servers, 2 Switches, 1 Router, 1 Wireless Router, 1 ISP

---

##  Security Implementations

| Section | Protocols/Controls                 |
|---------|------------------------------------|
| Admin   | 802.1X (planned, not implemented)  |
| HR      | VLAN 20 + Port Security            |
| R&D     | VLAN 30 + MAC Address Filtering    |
| Servers | Stateful Firewall + ACLs           |
| Wi-Fi   | WPA2-PSK with AES encryption       |

---

##  Theoretical Concepts Applied

- **VLANs** for segmentation
- **Subnetting** for IP management
- **MAC Filtering** for access control
- **Routing Protocols:** RIP & OSPF for multi-router simulation
- **NAT** for external access
- **ACLs** to secure server services
- **WPA2 Wi-Fi Encryption**

---

##  Files Included

- `smart-office-network.pkt` – Cisco Packet Tracer simulation file

---

##  Requirements

- **Cisco Packet Tracer** (Version 8.2+ recommended)

---

##  How to Use

1. Open the `.pkt` file in Cisco Packet Tracer.
2. Inspect VLAN assignments and port configurations on switches.
3. Test inter-VLAN communication and restrictions.
4. Verify wireless security and routing protocol behavior.
5. Explore server access via DNS or HTTP.

---

##  Notes


- Firewall ACLs are simulated via access lists on the router.
- The project focuses on **practical educational application** of core network design principles.

---

