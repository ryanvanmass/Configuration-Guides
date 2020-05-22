# Description
Run your Own VPN

# Installation and Configuration
1. Download and make executable
> `wget https://git.io/vpn -O openvpn-install.sh`

> `chmod 755 openvpn-install.sh`
2. Execute the script
> `./openvpn-install.sh`

# Auto Connect Clients
1. Convert the .ovpn file to .conf
> `cp file.ovpn file.conf`
2. copy the .conf file to /etc/openvpn
> `sudo mv file.conf /etc/openvpn`
3. start the service
> `sudo systemctl start openvpn@.conf file name`
4. enable to service to runb at start
> `sudo systemctl enable openvpn@.conf file name`
