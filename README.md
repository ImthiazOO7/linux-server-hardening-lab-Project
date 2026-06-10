# Linux Server Hardening Lab

A hands-on enterprise-level cybersecurity project demonstrating 
secure deployment and hardening of an Ubuntu Server 24.04.1 LTS 
virtual machine using industry-standard security controls.

## Project Overview
This lab simulates a real-world server hardening engagement, 
covering SSH hardening, firewall configuration, brute-force 
protection, intrusion detection, and post-hardening vulnerability 
scanning.

## Environment
- **OS:** Ubuntu Server 24.04.1 LTS
- **Virtualization:** VMware Workstation
- **Attacker Machine:** Kali Linux 2024.3
- **Target IP:** 192.168.234.130

## Security Controls Implemented

| Control | Tool | Status |
| SSH Hardening | OpenSSH 9.6p1 | ✅ Done |
| Host Firewall | UFW | ✅ Done |
| Brute-Force Protection | Fail2Ban | ✅ Done |
| Intrusion Detection | Suricata IDS v7.0.3 | ✅ Done |
| Vulnerability Scan | Nmap v7.94 | ✅ Done |

## Key Findings (Post-Hardening Nmap Scan)
- Only **1 port open** (22/tcp — SSH)
- 999 ports closed
- No unintended services exposed

## Tools Used
`Ubuntu Server` `Kali Linux` `OpenSSH` `UFW` `Fail2Ban` 
`Suricata` `Nmap` `VMware`

## Report
Full hardening report with screenshots available in `/report`

## Skills Demonstrated
- Linux server administration
- Network security & firewall configuration
- Intrusion Detection System (IDS) deployment
- Post-hardening verification & documentation
- Enterprise security checklist creation