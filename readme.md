# Wireshark Network Analysis Lab

Hands-on lab for network traffic analysis using **Wireshark**, focused on detecting insecure protocols and exposure of sensitive information.

This project is part of my cybersecurity portfolio and demonstrates basic network monitoring and analysis skills applicable to SOC environments.

---

## 🎯 Objetives

- Capture network traffic in a controlled environment
- Analyze common protocols (HTTP, DNS)
- Identify plaintext data transmission
- Document findings and security risks
- Propose mitigation measures

---

## 🧪 Lab Scenarios

The lab runs in an isolated virtual environment:

- **Kali Linux**: Traffic capture and analysis with Wireshark
- **Vulnerable server (DVWA / Metasploitable2)**: HTTP and DNS traffic generation
- **Network**: NAT / Host-only

> ⚠️ All captured traffic is from a laboratory environment.
> No real information or personal data is included.

---

## 🛠️ Tools

- Wireshark
- Kali Linux
- Metasploitable2 / DVWA
- VirtualBox / VMware

---

## 📁 Repository Structure

```text
wireshark-network-analysis-lab/
│
├── 01-lab-setup/
├── 02-traffic-capture/
├── 03-analysis/
├── 04-detections/
└── conclusions.md
