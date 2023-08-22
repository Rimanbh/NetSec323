# Network Security Project - Protecting a Network from Vulnerabilities and Attacks

This repository documents a practical project completed as part of the CCCY323 course. The project focused on implementing network defense tools and security measures to protect a network from vulnerabilities, threats, and attacks, as well as responding to incidents.

## Project Goals and Outcomes

- Demonstrated the use of network defense tools to safeguard the network from vulnerabilities, threats, and attacks. Employed passive attack techniques using Nmap to identify vulnerabilities.

- Analyzed and implemented security policies to protect the network. Explored firewall configurations to block unauthorized access, implemented logging to record packet drops, and incorporated Snort for intrusion detection.

## Approach

1. Set up a virtual environment with two VMs: one acting as the attacker and the other as the server.

2. Performed passive attack using Nmap to identify vulnerabilities on the server.

3. Captured network traffic using Wireshark on the server VM.

4. Detected server vulnerabilities and decided to implement firewalls.

5. Configured the server firewall to block attacker machine ports for "HTTP, SSH, FTP, and Telnet."

6. Enabled logging to record dropped packets and suspicious activities.

7. Deployed Snort to gather TCP scans of SSH connections on port 22.

8. Set up Snort rules to trigger alarms in case of intrusion detection.

## Usage

This repository provides insights into implementing network defense strategies and security measures to protect a network from vulnerabilities and attacks. It covers techniques such as passive scanning using Nmap, firewall configuration, and intrusion detection using Snort.

