## UPGRADE FOR DEBIAN 9 & 10
```
apt update -y && apt upgrade -y && apt dist-upgrade -y && reboot
```

##  UPGRADE FOR UBUNTU 19 & 20
```
apt update && apt upgrade -y && update-grub && sleep 2 && reboot
```

## INSTALL SCRIPT 
```
apt install -y && apt update -y && apt upgrade -y && wget -q https://raw.githubusercontent.com/nixyproject-cfd/autosc/main/ngingstall.sh && chmod +x ngingstall.sh && ./ngingstall.sh
```

## UPDATE SCRIPT
```
wget -q https://raw.githubusercontent.com/nixyproject-cfd/ns/main/ngapdet.sh && chmod +x ngapdet.sh && ./ngapdet.sh
```
