# Firewall

Hardware:
+ Intel 11 Jasper Lake
+ USB to Ethernet

Software:
+ Proxmox
  + pfSense or OpenWRT
  + VPN
  + DNS
  + DHCP

Error "pfsense stopped at kdb_enter+0x33"
-
9/30/25

I recieved this error trying to install pfsense bare. I saw there were better results if I virtualized instead.

Proxmox
-
10/01/25

I installed proxmox and resized my 'local' disk and renamed it to nvme.
Next I will be making a VM for pfSense.

PFsense
-
19/5/25

I have been tinkering around with the configurations of pfSense. I attempted to route traffic while double NAT-ing and nothing would get through. 
I can establish connectivity, but I couldn't recieve traffic. (If that makes any sense.)


pfSense
-
10/3/25
I created the VM for pfSense. I am okay with double NAT-ing for testing purposes. 
Prior to the creation of the VM, I needed to add an ethernet connection and linux bridge to Proxmox > Firewall > pfSense > Hardware
