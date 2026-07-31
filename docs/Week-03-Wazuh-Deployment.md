# Week 3 — Wazuh Deployment & Endpoint Monitoring

## Overview

I deployed Wazuh as the primary security monitoring platform for my SOC homelab. I configured agents, verified endpoint communication, and validated that Windows and Linux systems were successfully sending security events.

---

## Objectives

- Deploy the Wazuh Manager
- Configure the Wazuh Dashboard
- Install endpoint agents
- Verify agent connectivity
- Begin collecting security events

---

## Systems Connected

- Windows 11
- Kali Linux

---

## Skills Demonstrated

- SIEM / XDR deployment
- Endpoint monitoring
- Agent management
- Log collection
- Linux administration
- Troubleshooting

---

## Validation Performed

Successfully verified:

- Windows Security Events
- Linux authentication logs
- Agent connectivity
- Service health
- Dashboard functionality

---

## Challenges

Throughout deployment I encountered several issues involving:

- Agent communication
- Dashboard availability
- Service startup
- Storage limitations
- Log visibility

These issues required troubleshooting Linux services, verifying configurations, and ensuring all required components were running correctly.

---

## Lessons Learned

- Every security platform depends on healthy agent communication.
- Service status should always be verified before troubleshooting.
- Log collection is only valuable if events are reaching the dashboard.
