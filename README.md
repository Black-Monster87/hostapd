![](https://raw.githubusercontent.com/igorpecovnik/hostapd/master/bin/hostapd.png)

This is a script to compile, patch and pack hostapd deamon **from sources**. It can be used as a drop-in replacement **for Debian and Ubuntu** based distributions.

You can choose between four combinations:

- development 
- stable 

and

- default / all others  
- Realtek adapters

In all cases you get a new option **to control HT coexistance separate from noscan** - to force 40Mhz channels.


```bash
sudo apt-get -y install git
cd ~
git clone https://github.com/igorpecovnik/hostapd
chmod +x ./hostapd/go.sh
cd hostapd
./go.sh
```
