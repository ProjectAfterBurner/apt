# Project Afterburner Package Repository

### Raspberry Pi - Bullseye
To install:
```
sudo wget https://projectafterburner.github.io/apt/rpi/projectafterburner-rpi.list -O /etc/apt/sources.list.d/projectafterburner-rpi.list
wget -O- https://projectafterburner.github.io/apt/rpi/rpi.gpg | gpg --dearmor | sudo tee /usr/share/keyrings/projectafterburner-rpi-archive-keyring.gpg
sudo apt update
```
To remove:
```
sudo rm /etc/apt/sources.list.d/projectafterburner-rpi.list
sudo rm /usr/share/keyrings/projectafterburner-rpi-archive-keyring.gpg
```
