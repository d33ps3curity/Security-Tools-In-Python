# MAC Address
### Media Access Control
* Permanent
* Physical
* Unique

### Assigned by manufacturer

### Why change the MAC Address
* Increase anonymity
* Impersonate other devices
* Bypass filters

### How to change the MAC Address manually.
* root@kali ifconfig
* root@kali ifconfig eth0 down
* root@kali ifconfig eth0 hw ether 00.11.22.33.44.55(new mac_addr)
* root@kali ifconfig eth0 up
* root@kali ifconfig (check wether the mac changed or not)
