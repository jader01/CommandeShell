```bash
#commande ip :
ip addr add X.X.X.X/X dev ens3

#GW :
ip route add default via X.X.X.X dev ens3

#Config du proxy dans apt:
vi /etc/apt/apt.conf.d/proxy.conf
#ou
nano /etc/apt/apt.conf.d/proxy.conf

#Config du DNS :
vi /etc/resolv.conf
#ou
nano /etc/resolv.conf

#Stop le Network Manager :
systemctl stop NetworkManager

#Start le Network Manager :
systemctl stat NetworkManager

```
