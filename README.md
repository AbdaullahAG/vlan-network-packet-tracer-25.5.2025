# vlan-network-packet-tracer-25.5.2025
# VLAN Network Simulation using Cisco Packet Tracer

This project demonstrates the design and configuration of a basic enterprise LAN network using **VLANs** and **Router-on-a-Stick** setup in **Cisco Packet Tracer**.

## Network Description

The network consists of:

- **1 Router**
- **4 Switches**
  - 3 Access Switches (each connected to 3 end devices)
  - 1 Core Switch connecting all access switches and the router
- **9 End Devices (PCs)** divided into 3 VLANs

## VLAN Configuration

| VLAN | Description   | Subnet            | Default Gateway |
|------|---------------|-------------------|-----------------|
| 10   | Dept A        | 192.168.10.0/24   | 192.168.10.1    |
| 20   | Dept B        | 192.168.20.0/24   | 192.168.20.1    |
| 30   | Dept C        | 192.168.30.0/24   | 192.168.30.1    |

- Trunking is enabled between switches and the router (Router-on-a-Stick).
- Subinterfaces are created on the router to handle inter-VLAN routing.

## Technologies Used

- Cisco Packet Tracer
- VLANs
- Router-on-a-Stick (Subinterfaces with 802.1Q encapsulation)
- Trunk and Access port configurations
- Static IP addressing

## Topology Overview

> *Insert screenshot of your topology here if possible and name it `topology.png`.*

## How to Use

1. Open the `.pkt` file using **Cisco Packet Tracer (v8 or above)**.
2. Explore the topology and device configurations.
3. Test connectivity using the simulation tool or ping between devices in different VLANs.

## Educational Purpose

This project was developed as part of a university-level course in **Computer Networks Systems**, and showcases practical knowledge in:

- Network segmentation with VLANs
- Layer 3 routing between VLANs
- CLI and GUI configuration in Packet Tracer

---

