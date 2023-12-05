# Network Configuration Project

## Overview

This repository contains the configuration of a network topology implemented using Packet Tracer. The project includes IP addressing, routing, access control, NAT configuration, and DHCP setup. The network is divided into blocks, each serving a specific purpose.

## Project Tasks

### 1. IP Addressing

- Utilized VLSM to assign IP addresses.
- Assigned public and private IPs as per the provided information.
- Refer to "VLSM" file for specific allocations.

### 2. Subnetting

- Calculated required hosts per subnet based on student assignments.
- Applied VLSM for efficient IP address space utilization.

### 3. Routing Protocols

- Used EIGRP in the First Block.
- Configured OSPF with Area 1 in the Second Block.
- Implemented RIP in the Third Block.
- Used OSPF with Area 0 in the last block.

### 4. Redistribution

- Configured redistribution on Router6 and Router13.

### 5. DHCP Configuration

- Set up DHCP server in the first block for EIGRP, OSPF Area 1, and RIP.
- Configured separate DHCP server in OSPF Area 0.

### 6. NAT Configuration

- Implemented NAT on Router7 for the G network.

### 7. Access Control

- ACLs to restrict access:
  - One PC in Network L cannot access TFTP server.
  - One PC in Network E cannot access Data server.
  - All hosts in Network A cannot access Web Server.

## File Structure

- `PacketTracerProject.pkt`: Packet Tracer file with network topology.
- `PacketTracerVLSM.pdf`: IP address allocations for each network and VLSM.

## Usage

1. Open `PacketTracer_Project.pkt` using Cisco Packet Tracer.
2. Review the topology and configurations.
3. Refer to "PacketTracerVLSM.pdf" for IP address allocations.

## Contributors

- [Areeba Sattar]

Feel free to fork, clone, or contribute. For suggestions or improvements, open a pull request or issue.

Happy networking!
