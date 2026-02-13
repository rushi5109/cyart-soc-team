# Alert Priority Levels

## Objective
To understand how Security Operations Center (SOC) analysts prioritize alerts based on severity, business impact, and exploit likelihood.

## Priority Definitions

- Critical: Active exploitation, ransomware, data breach.
- High: Unauthorized administrative access.
- Medium: Suspicious login attempts or brute-force activity.
- Low: Port scans or informational alerts.

## Assignment Criteria

Alerts are prioritized based on:

- Asset Criticality (Production Server vs Test VM)
- Exploit Likelihood (Public exploit available)
- Business Impact (Financial or operational disruption)
- CVSS Score

## Example Case: Log4Shell

CVE-2021-44228  
CVSS Score: 9.8  
Priority Level: Critical  

Reason: Remote code execution vulnerability with public exploit.

## Tools Referenced

- CVSS (Common Vulnerability Scoring System)
- Splunk Risk Scoring
- NIST SP 800-61
