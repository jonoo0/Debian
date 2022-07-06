
## Debian on Termux Android
---------------
## Installation

Copy and paste this command to Termux

Debian 11.3.0 (Bullseye)
* Install Debian

```
pkg install wget -y && wget https://raw.githubusercontent.com/wahasa/Debian/main/11.3.0/install-debian && chmod +x install-debian && ./install-debian
```

* Install Debian-xfce

```
pkg install wget -y && wget https://raw.githubusercontent.com/wahasa/Debian/main/11.3.0/install-debian-xfce && chmod +x install-debian-xfce && ./install-debian-xfce
```

* Install Debian-lxde

```
pkg install wget -y && wget https://raw.githubusercontent.com/wahasa/Debian/main/11.3.0/install-debian-lxde && chmod +x install-debian-lxde && ./install-debian-lxde
```

Start Debian

```
./debian
```

Stop Debian

```
exit
```

=> Visit original site on [Andronix](https://github.com/AndronixApp/AndronixOrigin)

-----------

## VNC Viewer

* Start VNC Server

on Debian, run this command to start :

```
vncserver
```

* Open Vnc Viewer

Add (+) VNC Client to connect, fill with :

Address
> 127.0.0.1:5901

Name
> Debian 11

To disconnect VNC Client, click (X) on the right.

* Stop VNC Server

on Debian, run this command to stop :

```
vncserver-stop
```
-------------

