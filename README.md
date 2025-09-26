# HomeLab

9/25/2025
My documented journey to obtain my CCNA and next steps into Cybersec.
I have experimented with a Raspberry Pi 4B. I installed Pi-Hole w/ Unbound and used Pi-Hole as an DHCP.
Days later the RPi4B died. Note: This was found inside of a crypto miner I purchased some time ago and it was struggling to work then.

Currently, my plan is to create my own router using a tiny pc.
Instead of using a debian lite OS, I will use pfSense.

Subnetting my Network

Network: 192.168.68.0
Subnet Mask: 255.255.255.192

Total Subnets: 4
Total Hosts: 64

Net Address       Usable Hosts                  Broadcast
192.168.68.0      192.168.68.1-192.168.68.62    192.168.68.63
192.168.68.64     192.168.68.65-192.168.68.126  192.168.68.127
192.168.68.128    192.168.68.129-192.168.68.190 192.168.68.191
192.168.68.192    192.168.68.193-192.168.68.254 192.168.68.255
