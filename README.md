# AI SOC Analyst Agent - Home Lab

## Overview
A home lab project that simulates a SOC (Security Operations Center) environment using Ubuntu, Kali Linux, Python, and Airia AI to automatically detect and analyze suspicious network activity.

## Architecture
- **Kali Linux** - SOC machine running Python automation
- **Ubuntu** - Attacker/target machine generating network traffic
- **Airia AI** - AI agent that analyzes security alerts

## How It Works
1. Python script captures network traffic using tshark
2. Analyzes packet counts per source IP
3. Flags IPs exceeding threshold as suspicious
4. Generates structured alert JSON
5. Sends alert to Airia AI for intelligent analysis
6. AI responds with threat classification and recommendations

## Tools Used
- Python 3
- tshark / Wireshark
- Scapy
- Airia AI
- VirtualBox
- Kali Linux
- Ubuntu 24.04 LTS

## Skills Demonstrated
- Network traffic analysis
- SIEM/SOAR concepts
- Python automation
- AI integration
- SOC analyst workflow


