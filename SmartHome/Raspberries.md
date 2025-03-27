Raspberries
===========

ha : connect to wifi
--------------------

```sh
login
nmcli device wifi list
nmcli device wifi rescan
nmcli device wifi connect [SSID-Name] --ask
nmcli device wifi connect Itenium2025 --ask
ip address
```

If Home Assistant store is empty: Developer Tools > Restart

Wifi: Itenium2025 / DenBerg1840!


Install
-------

image: https://www.home-assistant.io/installation/raspberrypi/#downloading-the-home-assistant-image

Settings > Add-ons > Add-on Store (rechts vanonder)
Install:
- [ESPHome Device Builder](https://github.com/esphome/esphome)
    - Show in sidebar
- Terminal & SSH
    - Watchdog
    - Auto update
    - Show in sidebar

Open Terminal:

```sh
wget -O - https://get.hacs.xyz | bash -
```

Attention: In the "Home Assistant Install Guide.pdf" it says (incorrectly) `wget -o`!!


- Developer Tools > Restart > Restart Home Assistant
- Settings > Devices & services > + Add Integration (rechts onder)
    - hacs
    - Check the boxes like you own it
    - See "Home Assistant Guide.pdf"
- Goto [https://github.com/login/device](https://github.com/login/device)
- Home Assistant > HACS > Search for
  - card-mod
  - button-card
  - mini-graph-card
  - swipe-card
  - stack in card
  - For each "..." > Download


Configuration
-------------

- Settings > System > Network > Host name (ie: the-cloud-cottage.local:8123)
- Settings > People > _name_ > Update Login & Password (pi / home)
- Creating Encryption Key: Check steps "ESP flash steps.docs"
- Wifi: Itenium2025 / DenBerg1840!
  - Gateway: 172.16.10.254
  - Subnet: 255.255.252.0



During lunchbreak
-----------------

- Settings > Dashboards > Delete all but Overview and Energy
- Settings > Automations & scenes > Delete all
- Settings > Devices & services > ESPHome > Delete all devices
