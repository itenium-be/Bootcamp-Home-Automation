Raspberries
===========

homeassist5.local
User: pi / home

192.168.100.98:8123
homeassistant:8123


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
--> -O ?
```

- Developer Tools > Restart > Restart Home Assistant
- Settings > Devices & services > + Add Integration (rechts onder)
    - hacs --> not showing?

hostname: cb646a50-get



hacs
----

[Installation Instructions](https://www.hacs.xyz/docs/use/download/download/#to-download-hacs)

- [Visit](https://my.home-assistant.io/redirect/supervisor_addon/?addon=cb646a50_get&repository_url=https%3A%2F%2Fgithub.com%2Fhacs%2Faddons)
- Install hacs





Instellingen > Apparaten en diensten > + Integratie toevoegen (rechts onderaan) > Zoek
voor ‘hacs’ > klik alle boxes en verzend.
Ga naar https://github.com/login/device, login en paste de code die je van home assistant
krijgt.
Navigeer via het linker menu naar ‘HACS’ en download volgende mods: ‘card-mod’,
‘button-card’, ‘mini-graph-card’, ‘swipe-card’, ‘stack in card’.


IP of smartstopcontact
----------------------

static_ip: 192.168.0.111
gateway: 192.168.0.1
subnet: 255.255.255.0
