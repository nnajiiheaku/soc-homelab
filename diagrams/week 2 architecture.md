                         Internet
                            │
                    VirtualBox NAT
                            │
                         pfSense
              ┌─────────────┼─────────────┐
              │             │             │
        SOC Network    Victim Network  Attacker Network
       192.168.10.0/24 192.168.20.0/24 192.168.30.0/24
              │             │             │
       Ubuntu/Wazuh      Windows VM      Kali Linux
       192.168.10.x      192.168.20.x    192.168.30.x
