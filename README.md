# Network Troubleshooting & Connectivity Lab

## Overview

This project demonstrates a structured network troubleshooting workflow using Windows command-line tools. The goal is to validate host configuration, diagnose connectivity, and verify DNS and routing functionality through a layered diagnostic approach commonly used in IT support and SOC environments.

## Environment

Operating System: Windows

Network Type: DHCP-configured private network

Interface: Virtual Ethernet Adapter (VM environment)

IP Range: 172.16.8.0/24

## Tools Used

ipconfig – Network configuration validation

ping – Connectivity and reachability testing

nslookup – DNS resolution verification

tracert – Network routing path analysis

# Methodology
A layered troubleshooting approach was used to validate network functionality from local system to external connectivity.
### 1. Network Configuration Validation
The system’s IP configuration was reviewed to confirm DHCP assignment, subnet configuration, default gateway, and DNS settings.
### 2. Local Network Stack Verification
Loopback testing was used to confirm the integrity of the TCP/IP stack.
### 3. Connectivity Testing
Ping tests were used to validate communication with:

•Local host

•Default gateway

•External IP addresses

### 4. DNS Resolution Testing
DNS functionality was verified by resolving domain names into IP addresses.
### 5. Routing Path Analysis
Traceroute was used to observe the path traffic takes to reach external destinations and identify each hop in the network route.

# Key Findings
•TCP/IP stack is functioning correctly

•Local network connectivity is stable

•Default gateway is reachable

•DNS resolution is functioning as expected

•External routing path is established successfully

#### No packet loss or connectivity failures were observed during testing.

# Key Concepts Demonstrated
•Layered network troubleshooting methodology

•TCP/IP stack validation

•DNS resolution and analysis

•LAN vs WAN connectivity verification

•Basic routing and hop analysis

# Screenshots

Evidence is organized in the /screenshots directory and follows the troubleshooting sequence:

1.Network Configuration (ipconfig)

2.Connectivity Tests (ping)

3.DNS Resolution (nslookup)

4.Routing Analysis (tracert)

# Conclusion

This lab demonstrates foundational IT support and SOC-style troubleshooting skills using a structured diagnostic workflow. Each step isolates a specific layer of the network stack, enabling systematic identification and validation of network functionality.
