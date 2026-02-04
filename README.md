# cisco-packet-tracer-multi-office-routing
A dual-office network implementation featuring RIPv2 dynamic routing, IPv4 subnetting (/24 & /30), and Cisco CLI configuration. Includes a comprehensive technical report and end-to-end connectivity verification.

# Multi-Office Network Connectivity Project

## Overview
This project demonstrates the configuration of a dual-office network architecture using **Cisco Packet Tracer**. The design bridges two separate subnets (Office A and Office B) using **RIPv2 Dynamic Routing**.

## Key Technologies
- **Cisco IOS CLI**
- **RIPv2** (Routing Information Protocol)
- **Subnetting**: /24 for LANs and /30 for the WAN link
- **ICMP & ARP** verification

## Troubleshooting Success
During implementation, I resolved a routing table synchronization issue by enforcing **RIP Version 2** and disabling auto-summary, ensuring classless routing across the 10.0.0.0/30 WAN bridge.

## Project Contents
- **Report**: Full technical analysis and verification screenshots.
- **Lab File**: `.pkt` file for testing in Cisco Packet Tracer.
