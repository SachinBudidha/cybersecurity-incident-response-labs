# Phishing Incident Response

## Scenario
A suspicious email was detected by security monitoring tools indicating a potential phishing attempt targeting an internal user.

## Objectives
- Validate the alert and identify indicators of compromise (IOCs)
- Assess impact and scope
- Perform containment and remediation
- Document incident findings

## Investigation Steps
1. Analyzed sender domain, email headers, and message content
2. Identified suspicious URLs and sender reputation
3. Reviewed endpoint activity for post-click behavior
4. Correlated findings with threat intelligence sources
5. Mapped attacker techniques to MITRE ATT&CK

## Tools Used
- Email Header Analysis
- Microsoft Defender (Simulated)
- Threat Intelligence
- MITRE ATT&CK Framework

## Findings
- Malicious sender domain identified
- No endpoint compromise detected
- User interaction confirmed (email opened, link not clicked)

## Response Actions
- Email blocked at the gateway
- Sender domain blacklisted
- User notified and awareness guidance provided
- Incident documented and closed

## MITRE ATT&CK Mapping
- T1566 – Phishing
