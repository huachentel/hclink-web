# hclink-web

## Installation
```bash
git clone https://github.com/huachentel/hclink-web.git
mkdir /hclink (If the hclink directory exists, it is not required)
mkdir /data
rm -rf /hclink/*
tar -xvf hclink-web_x86.tar.gz -C /hclink (if x86)
tar -xvf hclink-web_arm.tar.gz -C /hclink (if arm)
/hclink/setup/ubuntu_setup.sh reinstall
cat /etc/hosts
    127.0.0.1 localhost  default
    #/etc/hosts It should contain what is shown above, and it needs to be added if it doesn't exist
reboot
```
## Access the web
```bash
1. PC accesses the network port of the equipment, and the network segment of the equipment should be set to be consistent with the PC.
2. Enter IP in the browser to access the page.
```

## Modify terminal IMEI:
```bash
vi /data/hclink/recovery/IMEI
```
