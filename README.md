# Wazuh_Soc_Lab
Home SOC lab using Wazuh SIEM to simulate and detect brute-force attacks
# Home SOC Lab – Wazuh SIEM

Built a home Security Operations Center (SOC) lab to simulate and detect cyber attacks.

## Lab Architecture
- Ubuntu VM running Wazuh SIEM
- Kali Linux VM as attacker machine
- Windows 10 endpoint monitored by Wazuh
- VirtualBox Host-Only network

## Attack Simulation
- Nmap reconnaissance scan to identify open ports
- Hydra SSH brute-force attack using rockyou wordlist

## Detection Results
- 1,565 total alerts generated
- 632 authentication failures detected
- MITRE ATT&CK technique detected: T1110 (Brute Force)

## Tools Used
- Wazuh
- Kali Linux
- Nmap
- Hydra
- VirtualBox
