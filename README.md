# 🔥 Firewall Configuration Task 

## Overview
Configured host-based firewalls on Linux to block Telnet (port 23) and allow secure access via SSH (port 22). Tested firewall rules and removed them to restore system state.

## Platform Used
- [ ] Linux (UFW)


## Key Commands (Linux)
- `sudo ufw enable`
- `sudo ufw deny 23`
- `sudo ufw allow 22`
- `sudo ufw delete deny 23`



## Summary
Firewalls act as the first line of defense by inspecting and filtering traffic. Blocking Telnet improves security posture by preventing weak remote access protocols.
