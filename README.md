
# Simple script to configure iptables firewall


## Install

```bash
git clone https://github.com/katsudouki/iptables-shell.git
cd iptables-shell
chmod +x iptables-shell.sh
sudo mv iptables-shell.sh /usr/bin/iptables-shell.sh
```
    
## Usage
to start the firewall run the command as root with sudo
```bash
sudo iptables-shell.sh start
```

to stop run
```bash
sudo iptables-shell.sh stop
```

and to 
to start the firewall run the command as root with sudo
```bash
sudo iptables-shell.sh unlock $PORT
```
Don't forget to replace $PORT with the port number