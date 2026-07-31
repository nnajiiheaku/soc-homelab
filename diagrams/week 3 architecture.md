                         Internet
                            │
                         pfSense
              ┌─────────────┼─────────────┐
              │             │             │
         SOC Network    Victim Network  Attacker Network
              │             │             │
       Wazuh Server      Windows VM      Kali Linux
       Manager           Wazuh Agent     Wazuh Agent
       Indexer                │               │
       Dashboard              └──── Logs ─────┘


Windows Wazuh Agent ──┐
                      ├──> Wazuh Manager ──> Wazuh Indexer ──> Dashboard
Kali Wazuh Agent ─────┘


<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/fa36ee18-ad7f-4c28-8aba-c6e1892bc91b" />
                    
