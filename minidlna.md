# Minidlna

MiniDLNA is a simple media server software, with the aim of being fully compliant with DLNA/UPnP-AV clients.

[minidlna debian wiki](https://wiki.debian.org/minidlna)

## Installation
```
sudo apt-get install minidlna
```

## Configuration

There is no GUI so you will have to use a text editor to make changes to the files listed below.
```
nano /etc/minidlna.conf
```
This is the main config file where most changes will be made.
```
nano /etc/default/minidlna
```
Change the user and group that the server is run as here.
```
nano /etc/init.d/minidlna
```
You should not have to change anything in this.
