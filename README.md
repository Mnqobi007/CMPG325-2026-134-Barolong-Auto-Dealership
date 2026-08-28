# CMPG325-2026-134 – Barolong Auto Dealership

## Project Information

- **Module:** CMPG 325 – Computer Networks
- **Project ID:** CMPG325-2026-134
- **Client ID:** CLI-134
- **Client:** Barolong Auto Dealership
- **Location:** Mahikeng
- **Industry:** Automotive
- **Address Block:** 172.30.88.0/23
- **Networking Challenge:** STP – Loop Prevention & Root Design

## Project Overview

This project involves the design and development of a computer network for Barolong Auto Dealership in Mahikeng.

The network is designed using the allocated IPv4 address block 172.30.88.0/23.

Cisco Packet Tracer will be used for the network implementation and simulation.

## Milestone 1 – Client Design Review

The Milestone 1 deliverables are:

1. Client Requirements
2. Physical Topology
3. Logical Topology
4. IP Addressing Plan
5. Initial GitHub Repository

## Client Requirements

The network must provide reliable connectivity for the dealership and appropriate logical separation of network traffic.

The design includes:

- Administration network
- Sales network
- Workshop/Service network
- Public/Guest Wi-Fi
- Network Management network
- Reserved addressing for the planned future branch

## Networking Challenge

The assigned networking challenge is:

**STP – Loop Prevention & Root Design**

The network contains redundant Layer 2 paths. Spanning Tree Protocol will be used to prevent Layer 2 switching loops and provide a controlled root bridge design.

The proposed STP design uses:

- **CORE-SW1** as the Primary Root Bridge
- **CORE-SW2** as the Secondary Root Bridge

## IP Addressing

The allocated address block is:

**172.30.88.0/23**

The initial logical networks are:

| VLAN | Purpose | Network |
|---|---|---|
| VLAN 10 | Administration | 172.30.88.0/26 |
| VLAN 20 | Sales | 172.30.88.64/26 |
| VLAN 30 | Workshop/Service | 172.30.88.128/26 |
| VLAN 40 | Public/Guest Wi-Fi | 172.30.88.192/26 |
| VLAN 50 | Network Management | 172.30.89.0/27 |
| VLAN 60 | Future Branch – Reserved | 172.30.89.32/27 |

## Wireless

Wireless connectivity is intended for the specified public areas.

The public/guest wireless network will be separated from the internal dealership networks.

## Change Request – CR6

A future branch office is planned.

The requirement is accommodated through network design and IP addressing only.

No second physical branch-office site is included in the current Packet Tracer design.

## Milestone 1 Status

- [x] Client Requirements
- [x] Physical Topology
- [x] Logical Topology
- [x] IP Addressing Plan
- [x] Initial GitHub Repository

## Future Development

Future project phases will include network configuration, VLAN configuration, routing, STP implementation, testing, troubleshooting and final documentation.
