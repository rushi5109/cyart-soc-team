# Capstone Project: Full Alert-to-Response Cycle

## Executive Summary

A vulnerability in Metasploitable2 was exploited using the vsftpd backdoor module. Wazuh detected suspicious activity and generated an alert mapped to MITRE T1190 (Exploitation of Public-Facing Application).

## Timeline

11:00 AM - Exploit Attempt Detected  
11:05 AM - Alert Generated  
11:15 AM - System Isolated  
11:30 AM - Attacker IP Blocked  

## Response Actions

- Compromised VM isolated.
- Attacker IP blocked using CrowdSec.
- Logs collected for investigation.
- Evidence hashed and documented.

## Recommendations

- Implement regular vulnerability scanning.
- Improve patch management.
- Enable proactive monitoring alerts.
