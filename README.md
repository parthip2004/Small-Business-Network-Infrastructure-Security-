# Small-Business-Network-Infrastructure-Security-
Designed and simulated a multi-department business network in Cisco Packet Tracer, implementing VLAN segmentation, inter-VLAN routing, DHCP, DNS, HTTP services, ACL-based access control, SSH management, and switch port security. Tech: Cisco IOS, VLAN, 802.1Q, Router-on-a-Stick, DHCP, DNS, ACL, SSH, Port Security (2026)



# Enterprise Network Infrastructure – Cisco Packet Tracer

A simulated enterprise network designed and configured using Cisco Packet Tracer.

## Project Overview

This project demonstrates the design and implementation of a small
enterprise network with multiple departments, VLAN segmentation,
inter-VLAN routing, DHCP, DNS, HTTP services, SSH management,
port security, and ACL-based traffic restrictions.

## Technologies Used

- Cisco Packet Tracer
- Cisco IOS
- VLAN
- Inter-VLAN Routing
- DHCP
- DNS
- HTTP
- SSH
- Access Control Lists (ACL)
- Switch Port Security

## Network Segmentation

| VLAN | Department | Network |
|------|------------|---------|
| 10 | IT | 192.168.10.0/24 |
| 20 | HR | 192.168.20.0/24 |
| 30 | Sales | 192.168.30.0/24 |
| 40 | Guest | 192.168.40.0/24 |

## Features

- VLAN-based network segmentation
- Inter-VLAN routing using Router-on-a-Stick
- DHCP address assignment
- DNS server configuration
- Internal HTTP web server
- SSH remote device management
- Switch port security
- Extended ACL traffic restrictions
- Department-based network isolation
- Network connectivity testing

## Network Topology

![Network Topology](screenshots/topology.png)

## Security

ACLs were configured to restrict unauthorized communication
between selected departmental VLANs.

Port security was enabled on access ports to restrict unauthorized
devices.

SSH was configured for secure remote management of network devices.

## Verification

Connectivity and services were tested using:

- ping
- ipconfig
- show vlan brief
- show interfaces trunk
- show ip interface brief
- show ip dhcp binding
- show access-lists
- show port-security

## Project Files

- `enterprise-network.pkt` – Cisco Packet Tracer project
- `configs/` – Router and switch configurations
- `screenshots/` – Project screenshots

## Author

Parthip Ts
