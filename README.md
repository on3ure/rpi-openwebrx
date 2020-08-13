# OpenWebRX Raspberry PI 3/4 #

### Install on Linux - Raspberry PI 4 ... Buster Release (2020) ###

## Install##
Download image from (OpenWebRX)[https://www.openwebrx.de/]

## Disable bluetooth & WiFi ##
```console
echo "dtoverlay=disable-bt,disable-wifi" | sudo tee -a /boot/config.txt
sudo systemctl disable hciuart
sudo reboot
```
