vpnmon - A VPN connection monitor for Ubuntu
======


Whenever your VPN connection disconnects, vpnmon disables your 
entire networking or runs a custom command of your choice.
This tool requires Network Manager to be installed or else it
would fail to function.

Licensed under GNU General Public License version 2


DEPENDENCIES:
1. Ubuntu

There isn't any sort of dependency checking mechanism at this 
time, so running Ubuntu is considered a requirement. However 
if you know what you are doing you should be able to get 
vpnmon running on any Linux distribution having:

1. python
2. gobject
3. dbus
4. NetworkManager
5. pynotify


INSTALL:
1. Extract the archive.
2. Run the "install" file.
3. Log out and then log in.
