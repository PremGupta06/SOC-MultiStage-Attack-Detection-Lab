# SOC-MultiStage-Attack-Detection-Lab


This project simulates a multi-stage cyber attack in a SOC lab environment using Kali Linux, Ubuntu Server, Wireshark, and Splunk.

The lab demonstrates:
- reconnaissance detection
- SSH brute-force attacks
- packet analysis
- log investigation
- SIEM monitoring

## Tools Used

- Kali Linux
- Ubuntu Server
- Wireshark
- Splunk Enterprise
- Hydra
- Nmap
- SSH

Kali Linux → Ubuntu Victim → Wireshark + Splunk Investigation

## Attacks Simulated

1. Nmap reconnaissance scanning
2. SYN stealth scanning
3. SSH brute-force attacks using Hydra
4. Authentication log analysis
5. SIEM log investigation

## Detection Workflow

- Captured network traffic using Wireshark
- Filtered SYN packets
- Monitored SSH traffic
- Investigated auth.log
- Imported logs into Splunk
- Identified brute-force patterns

## Findings

- Multiple SYN packets detected during Nmap scans
- Hydra generated repeated SSH authentication failures
- Ubuntu auth.log recorded failed login attempts
- Splunk successfully indexed authentication logs
- Attack timeline correlated across tools

## Skills Learned

- Reconnaissance detection
- Wireshark traffic analysis
- SSH brute-force investigation
- Linux log analysis
- Splunk SIEM monitoring
- SOC investigation workflow
