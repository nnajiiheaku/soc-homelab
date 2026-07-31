# Week 1 — Virtual Environment Setup

## Overview

During Week 1, I created the virtual infrastructure for my Enterprise SOC Homelab using VirtualBox.

The goal was to build the systems needed for a segmented cybersecurity environment before configuring networking, logging, monitoring, and detection tools.

---

## Systems Deployed

- pfSense
- Ubuntu Server
- Kali Linux
- Windows 11


---

## Objectives

- Install VirtualBox
- Create the required virtual machines
- Allocate CPU, memory, and storage
- Install each operating system
- Install VirtualBox Guest Additions where applicable
- Verify that each virtual machine starts correctly
- Create clean snapshots

---

## Virtual Machines

### pfSense

pfSense acts as the firewall and router for the homelab. It connects the lab networks and controls communication between them.

### Ubuntu Server

Ubuntu Server is used to host security tools and supporting services within the SOC network.

### Windows 11

Windows 11 represents the victim endpoint. It generates Windows event logs, Sysmon telemetry, account activity, and PowerShell activity.

### Kali Linux

Kali Linux represents the attacker system. It is used to safely perform scans and attack simulations against systems within the homelab.

---

## Snapshots

I created snapshots after completing the clean installation of each virtual machine.

Snapshots allow me to:

- Recover from configuration mistakes
- Restore a working system
- Safely test security tools
- Undo changes made during attack simulations

---

## Challenges

One challenge was correctly configuring VirtualBox Guest Additions. I also had to verify that each virtual machine had enough CPU, memory, and disk space without overloading the host computer.

---

## Lessons Learned

- Virtual machine resources must be planned carefully.
- Snapshots are important before making major configuration changes.
- Each system should have a clearly defined purpose.
- Building the infrastructure correctly makes later troubleshooting easier.

---

## Evidence

Screenshots from this stage will be stored in:

```text
screenshots/week1/
