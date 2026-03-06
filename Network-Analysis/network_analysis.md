# Network Security Analysis

## Objective
Analyze network structure and identify security risks.

## Tools Used

- Nmap
- Wireshark

## Network Scan

Example command:

nmap -sV 192.168.1.1

## Open Ports Identified

| Port | Service |
|-----|------|
| 22 | SSH |
| 80 | HTTP |
| 443 | HTTPS |

## Potential Risks

- Open SSH port may allow brute-force attacks
- HTTP service may expose web vulnerabilities

## Recommendations

- Implement firewall rules
- Restrict SSH access
- Enable HTTPS