# Week 5 — Splunk Deployment & Log Ingestion

## Overview

I focused on deploying Splunk Enterprise and integrating Windows event logs using the Splunk Universal Forwarder. The goal was to begin building a SIEM capable of collecting, searching, and visualizing security events.

---

## Objectives

- Install Splunk Enterprise
- Configure Splunk Web
- Install the Universal Forwarder
- Forward Windows Event Logs
- Verify log ingestion

---

## Components Deployed

- Splunk Enterprise
- Universal Forwarder
- Windows Event Collection
- Splunk Add-on for Microsoft Windows

---

## Skills Demonstrated

- SIEM Administration
- Log Ingestion
- Windows Event Collection
- Splunk Configuration
- Linux Administration
- Troubleshooting

---

## Troubleshooting

During deployment I investigated several issues including:

- Windows connectivity to Splunk
- VirtualBox networking
- Windows Firewall
- Universal Forwarder configuration
- Splunk services
- Boot-start configuration
- Event indexing

Troubleshooting these problems improved my understanding of both networking and SIEM deployment.

---

## Log Sources

Current data sources include:

- Windows Security Logs
- Windows System Logs
- Windows Application Logs
- Windows Powershell events
- Sysmon Events

---

## Lessons Learned

- Network connectivity is essential before troubleshooting SIEM configurations.
- The Universal Forwarder depends on correct network communication and configuration files.
- Verifying services and indexes is an important part of Splunk administration.
