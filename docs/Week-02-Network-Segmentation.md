# Week 2 — Network Segmentation with pfSense

## Overview

I configured pfSense to serve as the firewall and router for my SOC homelab. I segmented the environment into separate networks to simulate a real-world enterprise architecture.

---

## Objectives

- Deploy pfSense
- Configure network interfaces
- Create isolated networks
- Configure gateways
- Verify connectivity between systems

---

## Network Layout

SOC Network (192.168.10.0/24)
- Ubuntu Server
- Splunk
- Wazuh


Victim Network (192.168.20.0/24)
- Windows 11

Attacker Network (192.168.30.0/24)
- Kali Linux

---

## Skills Demonstrated

- Firewall configuration
- Network segmentation
- Routing
- Gateway configuration
- Basic firewall rule management
- Network troubleshooting

---

## Challenges

One of the biggest challenges was troubleshooting communication between virtual machines especially with Kali reaching Windows. I verified IP addressing, gateway configuration, VirtualBox adapters, and firewall rules to ensure systems could communicate as expected.

---

## Lessons Learned

- Network segmentation limits unnecessary communication between systems.
- Correct gateway configuration is essential for connectivity.
- Firewall rules determine what traffic is allowed between networks.
