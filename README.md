# Simulated Home Lab: HTTPS Traffic Analysis Using tcpdump
A hands-on packet analysis project demonstrating HTTPS communication using tcpdump on Linux.
## Overview

This project documents a simulated cybersecurity home lab in which live HTTPS network traffic was captured and analyzed using **tcpdump** on an Ubuntu virtual machine. The objective was to understand how secure web communication is established and maintained by observing packet-level network activity.

The analysis focuses on identifying key networking concepts including the TCP three-way handshake, encrypted HTTPS/TLS communication, multiple TCP connections, acknowledgments, connection termination, and HTTP/3 (QUIC) traffic.

---

## Objectives

- Capture live HTTPS network traffic using tcpdump
- Analyze the TCP three-way handshake
- Observe encrypted HTTPS/TLS communication
- Identify multiple TCP connections established by a modern web browser
- Analyze TCP acknowledgments and connection termination
- Observe UDP traffic associated with HTTP/3 (QUIC)

---

## Lab Environment

- **Host Operating System:** Windows 
- **Virtualization:** Oracle VirtualBox
- **Guest Operating System:** Ubuntu
- **Browser:** Firefox
- **Packet Capture Tool:** tcpdump
- **Network Mode:** NAT

---

## Skills Demonstrated

- Linux
- tcpdump
- Packet Analysis
- Network Traffic Analysis
- Cybersecurity Documentation

---

## Project Files

- **HTTPS Traffic Analysis Using tcpdump.pdf** – Complete technical report containing:
  - Lab Setup
  - Procedure
  - Packet Capture Methodology
  - Screenshots
  - Technical Analysis
  - Key Observations
  - Conclusion

---

## Key Concepts Covered

- TCP Three-Way Handshake
- Ephemeral Ports
- HTTPS/TLS Communication
- Multiple TCP Connections
- TCP Flags (SYN, ACK, PSH, FIN, RST)
- Connection Termination
- HTTP/3 (QUIC)
- UDP Port 443
- Packet Metadata Analysis

---

## Disclaimer

This project was conducted in a personal virtual lab environment. The packet captures contain only network metadata generated during normal web browsing and do not include decrypted HTTPS content or sensitive information.

---

## Author

**Irman Sharma**

Aspiring Cybersecurity Analyst
