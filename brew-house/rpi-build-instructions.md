# Instructions for Building a Brew House Image

1. update
2. Setup a static IP address
3. Setup a VPN server

```
# curl -L https://install.pivpn.io | bash
```

$ sudo pivpn add

(connect to 96.255.28.200, public ip)
OpenVPN.exe as adminstrator

4. Install VNC

```
$ sudo apt-get install tightvncserver
$ tightvncserver
```
Set VNC Server password
```
$ vncserver -kill :1
$ vncserver :1 -geometry 1920x1080 -depth 24 -dpi 96
```

4. Install Chromium
5. Install LAMP Stack
