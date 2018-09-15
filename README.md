# Zigbee2MQTT - Domoticz Python Plugin
Python plugin for Domoticz to add support for [zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) project

## Prerequisites

Finish setup and run zigbee2mqtt server (https://github.com/Koenkk/zigbee2mqtt/wiki)

## Installation

1. Clone repository into your domoticz plugins folder
```
cd domoticz/plugins
git clone https://github.com/stas-demydiuk/domoticz-zigbee2mqtt-plugin.git zigbee2mqtt
```
2. Restart domoticz
3. Go to "Hardware" page and add new item with type "Zigbee2MQTT"
4. Set your MQTT server address and port to plugin settings

Once plugin receive any message from zigbee2mqtt server it will try to create appropriate device.

## Supported devices

- Xiaomi / Aqara smart home cube
- Xiaomi Aqara double wireless wall switch

If your device is not listed here but zigbee2mqtt supports it, support can be added (fairly) easy by creating special adopter.