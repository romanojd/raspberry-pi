# Pi Slice 0005:  Setting a Static IP Address

Update the DHCP configuration file.

```
$ sudo nano /etc/dhcpcd.conf
```

Add the following lines to the end of the file.

```
interface eth0
static ip_address=192.168.1.16
static routers=192.168.1.1
static domain_name_servers=192.168.1.1
```

You could also setup a static IP address on a wireless network with ```interface wlan0```.

Reboot the Raspberry Pi.
```
$ sudo reboot
```

Confirm the configuration changes.
```
$ ifconfig
```
