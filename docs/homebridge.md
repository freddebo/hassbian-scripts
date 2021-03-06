## Description
This script will install and configure Homebridge to be used with Home Assistant.\
This will allow you to control your home with Apple's HomeKit (Siri on iOS, OSX and AppleTV).\
By default all devices are hidden, and you will need to add som entries in your `customize.yaml` configuration.\
You can learn more about this in the [Home Assistant for Homebridge repo.](https://github.com/home-assistant/homebridge-homeassistant#customization)

_NB!: This install script will fail resulting in your Pi to reboot, if you do not use an recommended level power supply._ 

*This suite can't be installed on Raspberry Pi Zero*

## Installation
```
$ sudo hassbian-config install homebridge
```

## Upgrade
No script available, maybe you could write one?\
If so, add an PR here when you are done:\
[homeassistant/hassbian-scripts](https://github.com/home-assistant/hassbian-scripts/pulls)

## Additional info
Description | Command/value
:--- | :---
Running as: | homebridge
Configuration dir: | /home/homebridge/.homebridge/
Start service: | `sudo systemctl start homebridge.service`
Stop service: | `sudo systemctl stop homebridge.service`
Restart service: | `sudo systemctl restart homebridge.service`
Service status: | `sudo systemctl status homebridge.service`
|
_You have to restart this service when changing configuration._

***
This script was originally contributed by [@Ludeeus](https://github.com/ludeeus).
