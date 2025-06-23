# Nmap-Port-Scanning
This project explores local network scanning using Nmap and basic packet monitoring using Wireshark. The goal was to identify active hosts, detect open ports, analyze services, and identify potential security risks from the open ports.

## Tools Used

- Nmap 7.97
- Wireshark
- macOS Terminal

## What I did

1. Installed Nmap & Wireshark
2. Scanned my IP range using TCP connect scan
3. Identified open ports 
4. Observed packets in Wireshark
5. Noted down potential security risks
6. Closed ports with `lsof` and `kill`

## Files

- `myscan.html` - HTML report
- `screenshot.png` - Wireshark view

## Command Summary

Main scan used:
```bash
sudo nmap -sT -sV 192.168.1.0/24

---

** Note **
For learning purposes only. Performed on a private network.
