# SOC-Lab-Threat-Detection-in-a-Segmented-Healthcare-Network
Project Overview

This project simulates a real-world Security Operations Center (SOC) environment within a healthcare organization. The goal was to design a secure network, detect cyber threats, and respond to incidents using a SIEM solution.

The lab focuses on improving visibility, threat detection, and incident response capabilities in a segmented network.

Lab Architecture

Network segmentation into:

WAN (Internet)

LAN (Internal network)

DMZ (Public-facing services)

Firewall implemented using pfSense

Centralized monitoring using Wazuh SIEM

Tools & Technologies

Wazuh (SIEM)

pfSense (Firewall)

Kali Linux (Attack simulation)

Wireshark (Packet analysis)

Nmap (Network scanning)

Hydra (Brute-force attacks)

VirtualBox (Lab environment)

Methodology

Designed and segmented the network using pfSense

Deployed Wazuh for centralized log collection

Simulated attacks using Kali Linux:

Brute-force login attempts (Hydra)

Network scanning (Nmap)

Captured and analyzed traffic using Wireshark

Correlated logs with SIEM alerts

Implemented automated response (IP blocking)

Key Findings

Multiple failed SSH login attempts detected (brute-force attack)

Internal network scanning activity identified

Suspicious traffic patterns confirmed via packet capture

Weak access controls and password policies were observed

Incident Response

Wazuh generated real-time alerts for suspicious activity

Automated firewall rules blocked attacker IP addresses

Attack traffic was successfully mitigated

Outcome

Improved network visibility through centralized logging

Faster detection and response to simulated threats

Demonstrated real-world SOC workflows (monitoring → detection → response)

Recommendations

Enforce strong password policies

Restrict unnecessary ports and services

Improve network segmentation controls

Implement continuous monitoring and alert tuning
