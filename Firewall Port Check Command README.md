## FortiGate IP Address Check Commands

### Check All Interface IPs


get system interface


### Show Detailed Interface Configuration


show system interface


### Check Specific Interface IP

Example for `port1`:


show system interface port1


### Quick Interface Status


get hardware nic port1


### Check Routing Table (Gateway & Networks)


get router info routing-table all


### Check ARP Table (Connected Devices)


get system arp


### Check Current Public IP (using ping source test)


execute ping 8.8.8.8


### Check DHCP Assigned IPs


execute dhcp lease-list
```

### Linux-style Interface Summary


diagnose ip address list


## Example Output


port1: 192.168.1.1/24
port2: 10.0.0.1/24
wan1 : 203.x.x.x


## Product Reference

FortiGate Firewall by [Fortinet](https://www.fortinet.com?utm_source=chatgpt.com)
