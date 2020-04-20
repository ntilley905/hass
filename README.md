# Home Assistant Configuration

Hello! Welcome to my Home Assistant configuration repo. Here I store all of my config files and I will attempt to explain them as best as I can below.

I use issues to document things that I want to implement in the future or things that are currently not working.

## Hardware

* Raspberry Pi 3B+ as Home Assistant Server
  * Addons:
    * [InfluxDB](https://github.com/hassio-addons/addon-influxdb) for long term data storage
    * [Nginx](https://github.com/hassio-addons/addon-nginx-proxy-manager) for reverse proxy
    * [MariaDB](https://github.com/home-assistant/hassio-addons/tree/master/mariadb) as required by Nginx
    * [Grafana](https://github.com/hassio-addons/addon-grafana)
    * [Samba](https://github.com/home-assistant/hassio-addons/tree/master/samba)
    * [SSH](https://github.com/hassio-addons/addon-ssh)
    * [AdGuard Home](https://github.com/hassio-addons/addon-adguard-home)
    * [Bitwarden RS](https://github.com/hassio-addons/addon-bitwarden)
    * [ESPHome](https://esphome.io/)
    * [Mosquitto](https://github.com/home-assistant/hassio-addons/tree/master/mosquitto)
    * [Node-RED](https://github.com/hassio-addons/addon-node-red) (not currently in use)
* Unifi Network
  * USG
  * Switch 8
  * AC AP Lite
  * Raspberry Pi 3B+ as controller
* Z-Wave
  * Aeotec Z-Stick Gen 5 as controller
  * 2x GE/Jasco In-Wall Smart Toggle Switch
  * 1x GE/Jasco In-Wall Smart Rocker Switch
  * 1x GE/Jasco In-Wall Smart Dimmer Switch
  * 4x Zooz ZSE40 4-in-1 Sensor
  * Ecolink Door & Window Sensor
  * Radio Thermostat CT100 Plus
* Philips Hue
* Shelly 2.5
* ESPHome
  * Bathroom and Bedroom
    * AM2302
    * TEMT6000
    * PIR
  * Fridge and Freezer
    * Dallas Temperature Sensor
    * Reed Switch
  * Outdoor Sensor
    * BME280
* Marantz SR5012 Audio Receiver
* Volumio on Raspberry Pi 3B+
* 2x Wemo Smart Plug 1st Gen

## Integrations

* ESPHome
* [HACS](https://hacs.xyz) Custom Components
  * [Apple TV](https://github.com/postlund/hass-atv-beta)
  * [NWS Weather Alerts](https://github.com/custom-components/weatheralerts)
  * [NWS Radar](https://github.com/MatthewFlamm/nwsradar)
  * [FAA Status](https://github.com/ntilley905/faastatus) (my own)
  * [Xfinity Usage](https://github.com/robert-alfaro/xfinity-usage)
* HEOS
* Philips Hue
* Mobile App
  * 3x iOS Integrations
* IQVIA for Pollen
* MQTT
  * Shelly Switches
* Unifi Controller
* Z-Wave
* HTTP
  * Cloudflare for DNS
* Discord Notifications
* NWS Weather
* Amcrest
* Python Script
  * [Shelly Auto Discovery](https://github.com/bieniu/ha-shellies-discovery) (via HACS)
* Google TTS
* Google Calendar

## Lovelace

* Main Dashboard
* Mobile Dashboard (WIP)
* Themes
  * [Slate](https://github.com/seangreen2/slate_theme) (via HACS)
* Custom Cards
  * [light-brightness-preset-row](https://github.com/finity69x2/light-brightness-preset-row)
  * [lovelace-auto-entities](https://github.com/thomasloven/lovelace-auto-entities)
  * [lovelace-template-entity-row](https://github.com/thomasloven/lovelace-template-entity-row)
  * [stack-in-card](https://github.com/custom-cards/stack-in-card)
