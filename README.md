# 🚀 Enterprise Campus Network Design

## 📌 Project Overview

This project is a multi-switch Enterprise Campus Network lab
designed and implemented using Cisco Packet Tracer.

The topology demonstrates Layer 2 network technologies and
enterprise switching concepts.

## 🏗️ Network Architecture

The topology is organized into:

- Core
- Distribution
- Access

> Note: The Core/Distribution/Access naming is used for
> organizational purposes. The lab uses Cisco Catalyst 2960
> Layer 2 switches.

## 🔧 Technologies Implemented

- VLANs
- 802.1Q Trunking
- VTP
- EtherChannel
- LACP
- STP
- CDP
- DTP
- Access Ports
- Basic Switch Security
- IP Addressing

## 🏢 VLAN Design

| VLAN | Department | Network |
|------|------------|---------|
| 10 | SALES | 192.168.10.0/24 |
| 20 | HR | 192.168.20.0/24 |
| 30 | IT | 192.168.30.0/24 |
| 40 | MANAGEMENT | 192.168.40.0/24 |

## ⚙️ Network Features

### VLAN Segmentation
Separate VLANs were created for each department.

### Trunking
802.1Q trunk links were configured between switches.

### VTP
VTP was implemented for VLAN database management.

### EtherChannel
LACP was configured to combine multiple physical links
into logical Port-Channels.

### STP
Spanning Tree Protocol was implemented to prevent Layer 2 loops.

### Security
Basic switch hardening was configured including:

- Enable Secret
- Console Password
- VTY Password
- Login configuration
- MOTD Banner

## 📁 Project Files

- `Enterprise-Campus-Network.pkt` — Cisco Packet Tracer project
- `Configurations/` — Switch configurations

## 🛠️ Software

Cisco Packet Tracer

## 👨‍💻 Author

Amr Khaled

#Cisco #Networking #CCNA #CCNP #NetworkEngineering
