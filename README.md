

# Network Configuration and Subnet Design

## Overview
This repository contains a detailed network configuration and subnet design assignment for the **EC 4060 – Computer and Data Network** course. The assignment focuses on setting up VLANs, configuring switches, routers, and other network components, and creating a subnet plan for a campus network.


## Contents
1. **Subnet Design**: Detailed IP addressing and subnet allocation for different network segments.
2. **VLAN Configuration**: Setup and verification of VLANs.
3. **Switch and Router Configuration**: Commands and steps for configuring switches, multilayer switches, and routers.
4. **Device Configurations**:
   - PC IP configurations
   - Printer restrictions
   - Wireless router setup
5. **Access Control**: Restriction policies for printers and other resources.
6. **Network Diagrams**:
   - IT Center Block
   - Department Block
   - Complete System Diagram

## Subnet Details
| VLAN Name                         | Needed Size | Allocated Size | IP Address Range        | Mask | Subnet Mask         |
|-----------------------------------|-------------|----------------|-------------------------|------|---------------------|
| Computer Lab 1 (I)               | 60          | 62             | 10.20.0.0 - 10.20.0.63 | 26   | 255.255.255.192     |
| Computer Lab 2 (I)               | 60          | 62             | 10.20.0.64 - 10.20.0.127 | 26   | 255.255.255.192     |
| Computer Vision & Machine Learning Lab | 50     | 62             | 10.20.1.0 - 10.20.1.63 | 26   | 255.255.255.192     |
| Digital Learning & Media Center  | 30          | 30             | 10.20.1.64 - 10.20.1.95 | 27   | 255.255.255.224     |
| ... (Additional entries omitted for brevity) |

Refer to the document for the full list of subnets.

## Key Configuration Steps
### VLAN Configuration
- VLANs were created and verified using the `show vlan` command.

### Switch Configuration
- Configured switches and multilayer switches for VLANs.

### Router Configuration
- Routers were set up to interconnect VLANs and enable inter-VLAN routing.

### Device IP Configuration
- PCs, printers, and wireless routers were configured with specific IPs based on the subnet design.

### Access Restrictions
- Printer access was restricted to specific blocks (e.g., IT Center Block).

## Network Diagrams
The network diagrams visually represent the system's architecture, including the IT Center block, department block, and overall network.

## Usage
This repository is intended for educational purposes, demonstrating how to design and implement a network for a campus environment with VLAN segmentation and proper subnet allocation.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
