# Descritpion
The File Transfer Protocol (FTP) allows you to transer files from one computer to another over a network

# Instalation
Debian: `sudo apt-get install vsftpd`

Arch: `sudo pacman -S vsftpd`

Fedora: `sudo dnf -y install vsftpd`

# Configuration
1. Open Config file
> `sudo nano /etc/vsftpd.conf`
2. Enable users to upload to FTP share

![alt text](https://github.com/ryanvanmass/Images/blob/master/Write%20Enable%20(VSFTPD).png "write_enable=YES")

3. Save and close config file
4. Restart the service
> `sudo service vsftpd restart`
or
> `sudo systemctl restart vsftpd`
