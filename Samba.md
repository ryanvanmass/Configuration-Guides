# Description
Samba allows you to share Folders over a network

# Installation
Debian: sudo apt-get install samba

Arch:

Fedora:

# Configuration
1. sudo nano /etc/samba/smb.conf
2. add the following at the bottom of config file for each share:

## Syntax

[Share Name]

> comment = Description of Share

> path = Path to folder
  
> read only = make the network share read only
 
> browseable = make the network share browseable or not

## Example

[Home]

> comment = Home Directory

> path = /home/ryanvanmass

> read only = no

> browseable = yes
