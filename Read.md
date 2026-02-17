# Task 4 - Firewall Configuration using UFW

## Objective
Configure and test basic firewall rules to allow or block traffic.

## Tool Used
UFW (Uncomplicated Firewall)

## Rules Configured
- Blocked Telnet (port 23)
- Allowed SSH (port 22)

## Commands Used
sudo ufw enable  
sudo ufw deny 23  
sudo ufw allow 22  
sudo ufw status numbered  

## Testing
- Tested SSH using: ssh localhost (success)
- Tested Telnet using: telnet localhost 23 (blocked)

## Result
Firewall successfully filtered network traffic based on defined rules.

## Learning
Understood how a firewall blocks or allows traffic based on ports.
