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

  <img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/96e70ecd-0fc0-4c8f-9591-10efabbbc82c" />

