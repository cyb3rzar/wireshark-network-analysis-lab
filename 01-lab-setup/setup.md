# Lab Setup

## Objective
Configure a controlled environment to capture and analyze network traffic
using Wireshark, focusing on insecure protocols and sensitive data exposure.

## Environment
- Analysis system: Kali Linux
- Target system: DVWA / Metasploitable2
- Network type: NAT / Host-only
- Capture tool: Wireshark

## Description
Two virtual machines were configured in an isolated network.
One machine generates web and DNS traffic, while the other captures
and analyzes the traffic using Wireshark.

## Security Considerations
All captured traffic belongs to a local lab environment.
No real information or personal credentials were used.
