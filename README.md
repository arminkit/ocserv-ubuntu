# ocserv-ubuntu
This Script is going to show you how to run your own VPN server by installing OpenConnect VPN server on Ubuntu 20.04 / 22.04. OpenConnect VPN server, aka ocserv, is an open-source implementation of Cisco AnyConnnect VPN protocol, which is widely used in businesses and universities. AnyConnect is an SSL-based VPN protocol that allows individual users to connect to a remote network.

## Installation
```bash
apt install nano wget -y
wget https://raw.githubusercontent.com/arminkit/ocserv-ubuntu/refs/heads/main/install-ocserv.sh
chmod +x install_script.sh
./install_script.sh
```

## Add User

```bash
ocpasswd -c /etc/ocserv/ocpasswd testuser
```

## Status Service

```bash
#status
systemctl ststus ocserv
#start
systemctl start ocserv
#stop
systemctl stop ocserv
#restart
systemctl restart ocserv
```

## Unistall Script
```bash
wget https://raw.githubusercontent.com/arminkit/ocserv-ubuntu/refs/heads/main/unistall-ocserv.sh
chmod +x unistall-ocserv.sh
./unistall-ocserv.sh
```
## 

Thank you for using Flags CSS! We hope it helps you create amazing international websites.

**Designed by ArminKiT**
