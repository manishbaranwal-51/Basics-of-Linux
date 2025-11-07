Introduction

In this module, I learned and practiced some basic *Networking* Linux commands.

6️⃣ Networking Commands (Command, Description & Example)

ip addr:
Show IP addresses and interfaces
ip addr show


ifconfig:
(Old) Show network interface details
ifconfig


ping:
Test network connectivity
ping google.com


nslookup:
Check DNS resolution
nslookup google.com


traceroute:
Trace route to a host
traceroute google.com


ssh:
Remote login via SSH	
ssh user@hostname


curl:
Send HTTP requests or check endpoints
curl https://example.com


wget:
Download files from web
wget https://example.com/file.zip


netstat -tuln:
Show open ports and listening services
netstat -tuln


ss -tuln:
Modern alternative to netstat
ss -tuln