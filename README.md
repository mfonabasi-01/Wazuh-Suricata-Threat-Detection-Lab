# SOC Threat Detection & Monitoring Lab

## Overview

This project demonstrates a small Security Operations Center (SOC) environment built to detect, analyze, and investigate suspicious network and endpoint activity.

The lab integrates **Wazuh SIEM, Suricata IDS, and VirusTotal threat intelligence**. A Kali Linux system was used to simulate reconnaissance activity against a monitored Ubuntu endpoint.

The environment was tested using:

- ICMP reconnaissance
- Nmap TCP SYN scanning
- Suricata network intrusion detection
- Wazuh SIEM alert monitoring
- File Integrity Monitoring (FIM)
- VirusTotal threat intelligence
- EICAR anti-malware test file

The project demonstrates a detection workflow from generating suspicious activity to detecting, centralizing, and investigating security events within Wazuh.

## Lab Environment

| Component | Purpose |
|---|---|
| Kali Linux | Simulated attacker and reconnaissance system |
| Ubuntu Linux | Monitored endpoint |
| Wazuh Agent | Endpoint monitoring and log collection |
| Wazuh Manager | SIEM analysis and centralized alerting |
| Suricata | Network Intrusion Detection System (IDS) |
| VirusTotal | Threat intelligence and file reputation |
| Nmap | Network reconnaissance simulation |
| EICAR | Safe anti-malware detection test |
