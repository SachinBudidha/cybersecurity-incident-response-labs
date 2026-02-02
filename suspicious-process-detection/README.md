# Suspicious Process Detection & Analysis (Simulated)

## Scenario
Security monitoring detected a suspicious process spawned from an unexpected parent process, indicating potential malicious activity.

## Investigation Steps
- Analyzed process name, command-line arguments, and execution path
- Reviewed parent-child process relationships
- Evaluated user context and privilege level
- Determined whether the activity aligned with normal behavior

## Tools Used
- Process Telemetry (Simulated Sysmon / EDR)
- Windows Event Analysis
- MITRE ATT&CK

## Findings
- Living-off-the-Land technique identified
- Abnormal parent-child process relationship observed
- Activity required escalation for further review

## Response Actions
- Suspicious process terminated (simulated)
- Host flagged for enhanced monitoring
- Incident escalated and documented

## MITRE ATT&CK Mapping
- T1059 – Command and Scripting Interpreter
- T1218 – Signed Binary Proxy Execution
