# CCNA Layer 2 Switching Lab

A simulated enterprise Layer 2 network built in Cisco Packet Tracer, applying core concepts from **CCNA Chapter 2** and beyond.

## 🧠 Lab Objectives

- Build a scalable Layer 2 network using best practices
- Practice VLAN creation and segmentation
- Configure EtherChannel for redundancy and load balancing
- Prevent loops using Spanning Tree Protocol
- Manage VLANs via VTP (VLAN Trunking Protocol)
- Enable Inter-VLAN routing on a multilayer switch
- Implement remote switch management via SSH

## 🧰 Technologies Used

- **VLANs**: 10 (HR), 20 (IT), 30 (Sales), 99 (Management), 100 (Servers)
- **VTP**: Server/Client mode for centralized VLAN management
- **STP**: Loop prevention and redundancy across Distribution switches
- **LACP (EtherChannel)**: Port-channeling across distribution and core
- **802.1Q Trunking**: VLAN tagging on trunk links
- **SSH**: Remote switch management from a laptop in VLAN 99
- **Core Gateway**: Multilayer switch performing Inter-VLAN routing and serving as default gateway
- **Trunk Security**: Trunks to server switches limited to VLAN 100 only

## 🖥️ Topology Overview

![Lab Topology (Logical)](ccna-layer2-switching-lab/blob/main/L2%20Lab.png)
![Lab Topology (Physical)]

## 📌 Notes

- Management VLAN (99) used for switch IP assignment and SSH access
- Laptops and PCs are assigned to VLANs according to department
- IP Phones use voice VLANs alongside data VLANs

## 🚀 Skills Demonstrated

- Network segmentation
- Redundancy & convergence planning
- Centralized VLAN control
- Layer 2 security and access
- Remote management and SSH hardening

## 🧑‍💻 Author

Rani Kamaleddine  
LinkedIn: https://www.linkedin.com/in/rani-kamaleddine/  
GitHub: https://github.com/r4n1-exe
