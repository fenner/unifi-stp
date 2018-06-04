# Spanning-tree Edge-port setting for UniFi Switches

This script downloads the device configuration from the
UniFi controller.  For any switch port that contains the
string `(EDGE)`, it logs into that switch, logs into the
configuration interface, and sets that port as a stp
edge port.

## Configuration

`${HOME}/.unifi.ini`

url: 
site:
username:
password:
