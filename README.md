# Week-2-Cybersecurity-Project
Week 2 cybersecurity project – OSINT footprinting and network scanning using Kali Linux.
# TheHarvester Footprinting & Zenmap Network Scanning

## Overview

This project demonstrates basic cybersecurity reconnaissance techniques using two tools available in Kali Linux:

- TheHarvester — for passive information gathering and footprinting
- Zenmap/Nmap — for network and host scanning

The activities were performed in a controlled lab environment for educational purposes.

## Objectives

The main objectives of this project were:

- Understand the concept of cybersecurity reconnaissance.
- Perform basic passive footprinting using TheHarvester.
- Identify publicly available information associated with a domain.
- Understand how missing API keys can affect information-gathering sources.
- Perform a local host scan using Zenmap.
- Examine host status, scanned ports, and network topology.
- Document the results and observations.

## Tools Used

| Tool | Purpose |
|------|---------|
| Kali Linux | Security testing environment |
| TheHarvester | Passive reconnaissance and information gathering |
| Zenmap | Graphical interface for Nmap |
| Nmap | Network and port scanning |
| VirtualBox | Virtual lab environment |

## 1. Footprinting with TheHarvester

TheHarvester was used to gather publicly available information associated with the selected domain.

The reconnaissance process included searches through available sources and attempted collection of:

- IP addresses
- Email addresses
- Hostnames
- Subdomains
- Associated people or organizational information

### Observation

Some searches returned no results, while other sources produced hostname/subdomain-related information.

The output also showed messages indicating that API keys were unavailable for several services. Therefore, the results should not be interpreted as a complete representation of the target's publicly available information.

## 2. Reporting TheHarvester Results

TheHarvester was also used to generate XML and JSON output files.

These files provide a structured record of the information collected during the reconnaissance activity and can be retained as project evidence.

## 3. Network Scanning with Zenmap

Zenmap was used to perform an Nmap scan against the local host:

`127.0.0.1`

The selected profile was:

`Intense scan`

The scan examined the local host and its ports.

### Observation

The scan identified:

- Host status: Up
- IPv4 address: 127.0.0.1
- Open ports: 0
- Filtered ports: 0
- Closed ports: 1000
- Scanned ports: 1000

The topology view displayed the local host as the scanned node.

## Results

The practical demonstrated two different stages of reconnaissance:

### Footprinting
TheHarvester can collect publicly available information from multiple sources. Results depend on the availability of sources, search engines, and API credentials.

### Network Scanning
Zenmap/Nmap can identify whether a host is reachable and provide information about the state of scanned ports.

## Key Learning Outcomes

Through this lab, I learned:

- The difference between passive footprinting and network scanning.
- How reconnaissance contributes to the information-gathering phase of cybersecurity.
- How TheHarvester can assist in collecting publicly available domain information.
- How Zenmap provides a visual interface for Nmap scanning.
- How to interpret open, closed, and filtered port states.
- The importance of documenting limitations when tools cannot access certain information sources.

## Evidence

Screenshots of the practical work are included in this repository to document the commands, tool output, and scan results.

## Ethical Considerations

This project was conducted for educational and cybersecurity-learning purposes in a controlled environment.

Reconnaissance and scanning should only be performed on systems, domains, and networks where appropriate authorization has been obtained.

## Conclusion

This lab provided practical experience with two important reconnaissance techniques: passive footprinting and network scanning. TheHarvester demonstrated the collection of publicly available information, while Zenmap demonstrated host and port scanning against a local system.

The project helped connect cybersecurity concepts with practical Kali Linux tools and real command-line output.

## Author

Cybersecurity Learning Project
