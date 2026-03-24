# Network Scan using Nmap

## Objective
Scan a target and identify open ports and services.

## Tools
- Nmap

## Command Used
nmap -sV scanme.nmap.org

## Results
See scan-results.txt for full output.

## Key Findings
- Port 22 open (SSH)
  Results

Scan performed on scanme.nmap.org

Open ports and services found:

22/tcp open ssh OpenSSH 6.6.1p1 Ubuntu
80/tcp open http Apache httpd 2.4.7
9929/tcp open nping-echo
31337/tcp open tcpwrapped

Filtered ports:

646/tcp filtered ldap

Full scan output is available in scan-results.txt
- Port 80 open (HTTP)
- Service detection shows Linux system

## Skills Demonstrated
- Network scanning
- Service enumeration
- Basic reconnaissance
