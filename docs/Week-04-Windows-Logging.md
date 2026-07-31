# Week 4 — Windows Logging & Sysmon

## Overview

Week 4 focused on increasing endpoint visibility by configuring Windows logging and Sysmon. The objective was to generate security telemetry that could later be analyzed in Wazuh and Splunk.

---

## Objectives

- Install Sysmon
- Configure Windows auditing
- Enable PowerShell logging
- Generate security events
- Validate log collection

---

## Logging Configured

- Windows Security Logs
- Process Creation
- PowerShell Activity
- Failed Logons
- Successful Logons
- Account Management
- Sysmon Events

---

## Security Events Tested

- Failed login attempts
- User account creation
- PowerShell execution
- Process creation
- Service changes

---

## Skills Demonstrated

- Windows Security Auditing
- Sysmon Configuration
- Event Viewer
- PowerShell
- Windows Security Monitoring

---

## Challenges

One of the largest challenges was ensuring that Windows security events were being generated and successfully forwarded to Wazuh.

This required validating:

- Audit policies
- Sysmon configuration
- Event IDs
- Windows Event Viewer
- Wazuh agent status

---

## Lessons Learned

- Windows does not log every activity by default.
- Proper auditing significantly increases visibility.
- Event IDs are critical when building detections.
