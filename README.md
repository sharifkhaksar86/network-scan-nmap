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
Port 22 open, SSH, OpenSSH 6.6.1p1 Ubuntu
Port 80 open, HTTP, Apache 2.4.7
Port 9929 open, Nping echo service
Port 31337 open, tcpwrapped

Filtered:

Port 646 filtered, LDAP

Full scan output is available in scan-results.txt
- Port 80 open (HTTP)
- Target is running a Linux based system

## Skills Demonstrated
- Network scanning
- Service enumeration
- Basic reconnaissance

- Network scanning  
- Service enumeration  
- Basic reconnaissance  

## Analysis

The scan identified multiple open services including SSH and HTTP.  
The presence of Apache and OpenSSH confirms a Linux based system.  
Filtered LDAP port suggests firewall or access control is in place.  
Traceroute shows multiple hops, indicating the host is externally reachable.  
