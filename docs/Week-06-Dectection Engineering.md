# Week 6 — Detection Engineering & Attack Simulation

## Overview
This week focused on moving from log collection into active detection
engineering. I simulated attacker behavior in the lab and validated whether
Windows, Sysmon, Splunk, and Wazuh generated and ingested the expected
security telemetry. I was to understand not only whether an event appeared, but
why it was generated, what fields were important, and how an analyst would
investigate the activity.

## Objectives
- Simulate suspicious activity against the Windows victim
- Validate Windows Security and Sysmon telemetry
- Analyze detections in Splunk and Wazuh
- Correlate attacker activity with endpoint logs
- Map activity to MITRE ATT&CK techniques
- Identify detection gaps and logging limitations

## MITRE ATT&CK Mapping
- T1110 — Brute Force / Credential Access
- T1059.001 — PowerShell
- T1136.001 — Create Account
- T1098 — Account Manipulation

## Skills Demonstrated
- Detection Engineering
- Threat Hunting
- Splunk SPL
- Wazuh Analysis
- Windows Security Event Analysis
- Sysmon Analysis
- MITRE ATT&CK Mapping
- Troubleshooting Audit Policies
- Attack Simulation
- Process Tree Analysis

## Lessons Learned
- A detection is only useful if the underlying telemetry exists.
- SIEM platforms cannot ingest events that the endpoint never generates.
- Process ancestry provides more context than process names alone.
- Windows audit policy directly affects available security telemetry.
- Different tools may display the same event fields differently.
- Process ancestry provides more context than process names alone.
- Windows audit policy directly affects available security telemetry.
- Different tools may display the same event fields differently.
- Endpoint logging and network IDS telemetry serve different purposes.
