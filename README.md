# Insure-Tech-Network-Security-Design
# Insure Tech Cybersecurity Overview

## Company Profile
- **Name:** Insure Tech
- **Location:** Toronto, Canada
- **Size:** 25 Employees
- **Services:** Homeowners, Health, Travel, Car, Life Insurance

## Key Assets
- **Physical and Digital:** Office space, servers, network devices, cloud services, data centers, 
- **Human Resources:** Underwriters, policy agents, sales, customer service, tech, financial, marketing teams
- **Sensitive Data:** Customer and employee information, contracts, and agreements

## Protection Objectives
- **Regulatory Compliance:** ISO, HIPAA, GDPR
- **Physical Security:** Configured devices, secure VPN access
- **Data Security:** Compliance with HIPAA and GDPR to prevent breaches
- **Operational Continuity:** Secure software, systems, and cloud services

## Network Diagram
<p align="center">
  <img src="https://i.imgur.com/yE7xIwy.png" alt="Network Diagram" /><br/>
  Network Diagram
</p>


## Network Architecture
- **Firewalls:** Dual next-gen firewalls with IDS/IPS for traffic management and redundancy
- **Routing:** Dual routers for enhanced connectivity and reliability
- **Segmentation:** Departmental network sections with unique IP ranges
- **Load Balancers & WAF:** Manage traffic, protect web servers, divert threats to honeypots
- **DMZ & Clustering:** Secure database access and improve availability
- **Wi-Fi & Proxy:** Secure Wi-Fi with WPA3 Enterprise, forward proxy for outbound traffic
- **Identity Management:** Hybrid AD with MFA for secure access
- **Monitoring:** Wazuh FIM, Splunk SOAR, EDR for real-time activity insights
- **Cloud Strategy:** Hybrid cloud (Azure, AWS) for disaster recovery

## Security Analysis

### Confidentiality
- **WAF & NGFW:** Block unauthorized access, monitor traffic
- **DMZ:** Isolate critical business information
- **EDR & IAM:** Validate access, prevent unauthorized data transfer
- **Deception Technology:** Honeypots to divert and study attackers

### Integrity
- **WAF & NGFW:** Protect against data alteration and malware
- **Wazuh FIM:** Monitor file changes
- **Backup Servers:** Ensure data recovery and accuracy

### Availability
- **Splunk SOAR:** Optimize threat response, ensure continuous service
- **Load Balancers & Backup Servers:** Distribute traffic, ensure recovery

## Threats and Vulnerabilities
- **External:** Cyberattacks, unauthorized access, data breaches
- **Internal:** Insider threats, accidental data loss
- **Vulnerabilities:** Weak passwords, outdated software, DMZ exposure, cloud dependency, social engineering

## Risk Mitigation
- **Confidentiality:** Encryption, access controls, DLP, employee training
- **Integrity:** Hashing, FIM, backups
- **Availability:** Redundancy, load balancing, disaster recovery planning, network monitoring

## Cybersecurity Teams
- **Blue Team:** SOC analysts, Threat Intelligence Engineers
- **Security Awareness & Training:** Develops and implements training programs
- **Digital Forensics:** Gathers and analyzes evidence for legal and investigative processes
