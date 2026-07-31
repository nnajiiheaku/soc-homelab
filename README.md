# Enterprise SOC Homelab

## Overview

This repository documents my journey building an enterprise-style Security Operations Center (SOC) homelab from scratch.

The objective is to gain hands-on experience with enterprise security tools by deploying, configuring, and testing a realistic cybersecurity environment.


## Lab Architecture

```
                 Internet
                     │
                ┌─────────┐
                │ pfSense │
                └────┬────┘
                     │
      ┌──────────────┼──────────────┐
      │              │              │
┌──────────┐   ┌──────────┐   ┌──────────┐
│    SOC   │   │  Victim  │   │ Attacker │
│192.168.10│   │192.168.20│   │192.168.30│
└────┬─────┘   └────┬─────┘   └────┬─────┘
     │              │              │
 ┌────────┐     ┌─────────┐     ┌────────┐
 │ Splunk │     │Windows11│     │  Kali  │
 ├────────┤     └─────────┘     └────────┘
 │ Wazuh  │
 └────────┘
```

---

## Tech Stack

- Splunk Enterprise
- Wazuh
- pfSense
- Kali Linux
- Windows 11
- Ubuntu Server
- VirtualBox
- Sysmon
- PowerShell

---

## Current Progress

- ✅ Week 1 – Virtual Environment Setup
- ✅ Week 2 – Network Segmentation
- ✅ Week 3 – Wazuh Deployment
- ✅ Week 4 – Windows Logging & Sysmon
- ✅ Week 5 – Splunk Deployment
- 🚧 Week 6 – Detection Engineering

---

## Repository Structure

- `docs/` – Weekly documentation
- `screenshots/` – Images from the lab
- `diagrams/` – Network diagrams
- `detections/` – Splunk searches and Wazuh alerts
- `configs/` – Configuration files

---

## Goal

Build a production-style SOC environment while documenting every stage of the process and developing practical security engineering skills.
