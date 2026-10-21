# HomeAssistant Config


[![GitHub stars](https://img.shields.io/github/stars/alesus97/homeassistant-config)](https://github.com/alesus97/homeassistant-config)
[![GitHub last commit](https://img.shields.io/github/last-commit/alesus97/homeassistant-config)](https://github.com/alesus97/homeassistant-config/commits/master)
[![Home Assistant Version](https://img.shields.io/badge/dynamic/json?url=https://raw.githubusercontent.com/alesus97/homeassistant-config/main/.ha_run.lock&query=$.ha_version&label=Home%20Assistant&color=41BDF5&logo=home-assistant&style=for-the-badge)](https://www.home-assistant.io/)
# Devices


| Device  | Image|Quantity | Connection | Home Assistant | Notes |
| -------------| ------ | :---: | ------------- | ------------- | ------------- |
| [Sonoff Mini](https://amzn.to/2HlmcED) | ![](https://i.ibb.co/rd2Bb1L/41-WVzq-Dw7-TL-AC-SX425.jpg) | 6 | Wi-Fi | [MQTT]| [DIY](https://tasmota.github.io/docs/Sonoff-DIY/)  jumper [Tasmota] flashed|
| [Sonoff Dual](https://amzn.to/2UIeJCw) | ![](https://i.ibb.co/Dw1w9yz/Sonoff-Dual.jpg) |2 | Wi-Fi| [MQTT]| Hardware [Tasmota] flashed|
| [Blitzwolf BW-SHP2](https://amzn.to/336IQIy) | ![](https://i.ibb.co/2sbbsmy/Blitzwolf-BW-SHP2.jpg) |2 | Wi-Fi| [MQTT]| [Tasmota] flashed with [tuya-convert](https://github.com/ct-Open-Source/tuya-convert)|
| [Wifi RGB Controller](https://amzn.to/397N1Yt) | ![](https://i.ibb.co/P5f90mg/rgb-Controller.jpg) | 2 | Wi-Fi| [Flux Led](https://www.home-assistant.io/integrations/flux_led/) | Led strip RGB controller|
| [Xiaomi Aqara Multisensor](https://amzn.to/35N2JWE) |![](https://i.ibb.co/hskTfq3/aqara-Multisensor.jpg) | 5 | Zigbee| [deConz]| Temperature, humidity, pressure and battery sensor|
| [Broadlink RM3Mini](https://amzn.to/2IW48kU) |![](https://i.ibb.co/6Z01sk1/Broadlink-RM3-Mini.jpg) | 1 | Wi-Fi| [Broadlink]| Universal infrared remote|
| [Conbee II](https://amzn.to/2IW48kU) |![](https://i.ibb.co/Hzpr7Ph/conbee2-aquacolor2.jpg) | 1 | USB| [deConz] | USB Zigbee gateway|


# New Features!

<!-- readme-updater:features:start -->
Recent configuration changes (commit dates and subjects):

- **2026-10-17**: Aggiornato la versione di HA a 2026.10.1, modificato file di configurazione e aggiunti nuovi script e template per la gestione delle scadenze del Golf 8.
- **2026-08-17**: reinserita history
- **2026-08-17**: Suddivisa configurazione in più file, rimossi file non utilizzati
- **2026-08-11**: Aggiunti sensori di costo spine 1 e 2, aggiunti sensori di versione fw tasmota, aggiunto sensore temp cpu prelevata da proxmox. Aggiornata versione a 2026.8.1
- **2025-12-28**: Aggiornata configurazione
- **2024-12-29**: Corretto target_sensor climate, modificata soglia ban ip a 10
- **2024-12-26**: Aggiornato HA
- **2024-12-06**: first commit
<!-- readme-updater:features:end -->

  - **16.11.2020**: ESP32 and DS18B20 MQTT Temperature 
  - **23.11.2020**: Startup sync automation (Lights, Covers and Climate)

# Integration & Addons

Installed custom integrations and HACS resources. Built-in integrations share the Home Assistant Core version.
Versions come from local manifests, HACS installed metadata and Supervisor, not upstream releases.

| Plugin | Type | Source | Installed Version | Repository / Documentation |
| ------ | ---- | ------ | ----------------- | -------------------------- |
| Alexa Media Player | Integration | HACS | 5.17.1 | https://github.com/alandtse/alexa_media_player |
| artem-sedykh/mini-climate-card | Frontend | HACS | v3.4.0 | https://github.com/artem-sedykh/mini-climate-card |
| azuwis/zigbee2mqtt-networkmap | Frontend | HACS | v0.13.0 | https://github.com/azuwis/zigbee2mqtt-networkmap |
| Battery Notes | Integration | HACS | 3.7.2 | https://github.com/andrew-codechimp/HA-Battery-Notes |
| benct/lovelace-multiple-entity-row | Frontend | HACS | v4.13.0 | https://github.com/benct/lovelace-multiple-entity-row |
| bramkragten/swipe-card | Frontend | HACS | v5.0.0 | https://github.com/bramkragten/swipe-card |
| bramkragten/weather-card | Frontend | HACS | v1.5.0 | https://github.com/bramkragten/weather-card |
| Clooos/Bubble-Card | Frontend | HACS | v3.4.2 | https://github.com/Clooos/Bubble-Card |
| custom-cards/button-card | Frontend | HACS | v7.0.1 | https://github.com/custom-cards/button-card |
| custom-cards/flex-table-card | Frontend | HACS | v1.5 | https://github.com/custom-cards/flex-table-card |
| custom-cards/stack-in-card | Frontend | HACS | 0.2.0 | https://github.com/custom-cards/stack-in-card |
| denysdovhan/vacuum-card | Frontend | HACS | v2.12.0 | https://github.com/denysdovhan/vacuum-card |
| Drivvo | Integration | HACS | 3.1.0 | https://github.com/hudsonbrendon/HA-drivvo |
| elax46/custom-brand-icons | Frontend | HACS | 2026.10.1 | https://github.com/elax46/custom-brand-icons |
| HACS | Integration | HACS | 2.0.5 | https://github.com/hacs/integration |
| HomeAssistant Cupertino Icons | Integration | HACS | 5.0.1 | https://github.com/menahishayan/HomeAssistant-Cupertino-Icons |
| homeassistant-extras/pi-hole-card | Frontend | HACS | 0.29.0 | https://github.com/homeassistant-extras/pi-hole-card |
| iantrich/config-template-card | Frontend | HACS | 1.3.6 | https://github.com/iantrich/config-template-card |
| kalkih/mini-graph-card | Frontend | HACS | v0.13.0 | https://github.com/kalkih/mini-graph-card |
| kalkih/mini-media-player | Frontend | HACS | v1.16.12 | https://github.com/kalkih/mini-media-player |
| maxwroc/battery-state-card | Frontend | HACS | v4.2.0 | https://github.com/maxwroc/battery-state-card |
| Monitor Docker | Integration | HACS | 1.20b3 | https://github.com/ualex73/monitor_docker |
| NemesisRE/kiosk-mode | Frontend | HACS | v15.0.0 | https://github.com/NemesisRE/kiosk-mode |
| Nezz/homeassistant-visionos-theme | Theme | HACS | 4.2.2 | https://github.com/Nezz/homeassistant-visionos-theme |
| nielsfaber/scheduler-card | Frontend | HACS | v4.0.19 | https://github.com/nielsfaber/scheduler-card |
| Node-RED Companion | Integration | HACS | 4.3.2 | https://github.com/zachowj/hass-node-red |
| ofekashery/vertical-stack-in-card | Frontend | HACS | v1.1.4 | https://github.com/ofekashery/vertical-stack-in-card |
| piitaya/lovelace-mushroom | Frontend | HACS | v5.2.3 | https://github.com/piitaya/lovelace-mushroom |
| Playnite Web MQTT | Integration | HACS | 0.0.12 | https://github.com/cvele/playnite_web_mqtt |
| Remote Home-Assistant | Integration | HACS | 4.6 | https://github.com/custom-components/remote_homeassistant |
| RomRider/apexcharts-card | Frontend | HACS | v2.2.3 | https://github.com/RomRider/apexcharts-card |
| SmartIR | Integration | HACS | 1.18.1 | https://github.com/smartHomeHub/SmartIR |
| Sonoff | Integration | HACS | 3.13.2 | https://github.com/AlexxIT/SonoffLAN |
| Tapo: Cameras Control | Integration | HACS | 7.2.8 | https://github.com/JurajNyiri/HomeAssistant-Tapo-Control |
| TCL Home - Unofficial | Integration | HACS | 3.16.0 | https://github.com/nemesa/ha-tcl-home-unofficial-integration |
| thomasloven/lovelace-auto-entities | Frontend | HACS | v1.16.1 | https://github.com/thomasloven/lovelace-auto-entities |
| thomasloven/lovelace-card-mod | Frontend | HACS | v4.2.1 | https://github.com/thomasloven/lovelace-card-mod |
| thomasloven/lovelace-layout-card | Frontend | HACS | v2.4.7 | https://github.com/thomasloven/lovelace-layout-card |
| thomasloven/lovelace-template-entity-row | Frontend | HACS | v1.4.1 | https://github.com/thomasloven/lovelace-template-entity-row |
| usernein/tailwindcss-template-card | Frontend | HACS | v3.1.1 | https://github.com/usernein/tailwindcss-template-card |
| Volkswagen Connect | Integration | HACS | v5.5.1 | https://github.com/robinostlund/homeassistant-volkswagencarnet |
| VW Group Connect | Integration | HACS | 5.1.1 | https://github.com/its-me-prash/vwgroup-connect-ha |
| wassy92x/lovelace-digital-clock | Frontend | HACS | v1.2.4 | https://github.com/wassy92x/lovelace-digital-clock |

### Add-ons

<!-- readme-updater:addons:start -->

| Plugin | Type | Source | Installed Version | Repository / Documentation |
| ------ | ---- | ------ | ----------------- | -------------------------- |
| Advanced SSH & Web Terminal | Add-on | Supervisor | 24.1.7 | https://github.com/hassio-addons/app-ssh |
| deCONZ | Add-on | Supervisor | 8.8.0 | https://github.com/home-assistant/addons/tree/master/deconz |
| Duck DNS | Add-on | Supervisor | 2.0.1 | https://github.com/home-assistant/addons/tree/master/duckdns |
| ESPHome Device Builder | Add-on | Supervisor | 2026.10.0 | https://esphome.io/ |
| Get HACS | Add-on | Supervisor | 1.3.1 | https://github.com/hacs/addons/tree/main/get |
| Home Assistant Google Drive Backup | Add-on | Supervisor | 0.112.1 | https://github.com/sabeechen/hassio-google-drive-backup |
| Let's Encrypt | Add-on | Supervisor | 6.5.0 | https://github.com/home-assistant/addons/tree/master/letsencrypt |
| Mosquitto broker | Add-on | Supervisor | 7.1.2 | https://github.com/home-assistant/addons/tree/master/mosquitto |
| NGINX Home Assistant SSL proxy | Add-on | Supervisor | 4.5.1 | https://github.com/home-assistant/addons/tree/master/nginx_proxy |
| Node-RED | Add-on | Supervisor | 22.1.0 | https://github.com/hassio-addons/app-node-red |
| RPC Shutdown | Add-on | Supervisor | 3.0 | https://github.com/home-assistant/addons/tree/master/rpc_shutdown |
| Samba share | Add-on | Supervisor | 12.10.0 | https://github.com/home-assistant/addons/tree/master/samba |
| SQLite Web | Add-on | Supervisor | 6.1.1 | https://github.com/hassio-addons/app-sqlite-web/tree/main/README.md |
| Studio Code Server | Add-on | Supervisor | 7.2.0 | https://github.com/hassio-addons/app-vscode |
| TasmoAdmin | Add-on | Supervisor | 0.34.0 | https://github.com/hassio-addons/app-tasmoadmin |
| TasmoBackup | Add-on | Supervisor | 1.08.00 | https://github.com/danmed/TasmoBackupV1/ |
| Terminal & SSH | Add-on | Supervisor | 10.5.0 | https://github.com/home-assistant/addons/tree/master/ssh |

<!-- readme-updater:addons:end -->

<!-- readme-updater:inventory ["| Alexa Media Player | Integration | HACS | 5.17.1 | https://github.com/alandtse/alexa_media_player |", "| artem-sedykh/mini-climate-card | Frontend | HACS | v3.4.0 | https://github.com/artem-sedykh/mini-climate-card |", "| azuwis/zigbee2mqtt-networkmap | Frontend | HACS | v0.13.0 | https://github.com/azuwis/zigbee2mqtt-networkmap |", "| Battery Notes | Integration | HACS | 3.7.2 | https://github.com/andrew-codechimp/HA-Battery-Notes |", "| benct/lovelace-multiple-entity-row | Frontend | HACS | v4.13.0 | https://github.com/benct/lovelace-multiple-entity-row |", "| bramkragten/swipe-card | Frontend | HACS | v5.0.0 | https://github.com/bramkragten/swipe-card |", "| bramkragten/weather-card | Frontend | HACS | v1.5.0 | https://github.com/bramkragten/weather-card |", "| Clooos/Bubble-Card | Frontend | HACS | v3.4.2 | https://github.com/Clooos/Bubble-Card |", "| custom-cards/button-card | Frontend | HACS | v7.0.1 | https://github.com/custom-cards/button-card |", "| custom-cards/flex-table-card | Frontend | HACS | v1.5 | https://github.com/custom-cards/flex-table-card |", "| custom-cards/stack-in-card | Frontend | HACS | 0.2.0 | https://github.com/custom-cards/stack-in-card |", "| denysdovhan/vacuum-card | Frontend | HACS | v2.12.0 | https://github.com/denysdovhan/vacuum-card |", "| Drivvo | Integration | HACS | 3.1.0 | https://github.com/hudsonbrendon/HA-drivvo |", "| elax46/custom-brand-icons | Frontend | HACS | 2026.10.1 | https://github.com/elax46/custom-brand-icons |", "| HACS | Integration | HACS | 2.0.5 | https://github.com/hacs/integration |", "| HomeAssistant Cupertino Icons | Integration | HACS | 5.0.1 | https://github.com/menahishayan/HomeAssistant-Cupertino-Icons |", "| homeassistant-extras/pi-hole-card | Frontend | HACS | 0.29.0 | https://github.com/homeassistant-extras/pi-hole-card |", "| iantrich/config-template-card | Frontend | HACS | 1.3.6 | https://github.com/iantrich/config-template-card |", "| kalkih/mini-graph-card | Frontend | HACS | v0.13.0 | https://github.com/kalkih/mini-graph-card |", "| kalkih/mini-media-player | Frontend | HACS | v1.16.12 | https://github.com/kalkih/mini-media-player |", "| maxwroc/battery-state-card | Frontend | HACS | v4.2.0 | https://github.com/maxwroc/battery-state-card |", "| Monitor Docker | Integration | HACS | 1.20b3 | https://github.com/ualex73/monitor_docker |", "| NemesisRE/kiosk-mode | Frontend | HACS | v15.0.0 | https://github.com/NemesisRE/kiosk-mode |", "| Nezz/homeassistant-visionos-theme | Theme | HACS | 4.2.2 | https://github.com/Nezz/homeassistant-visionos-theme |", "| nielsfaber/scheduler-card | Frontend | HACS | v4.0.19 | https://github.com/nielsfaber/scheduler-card |", "| Node-RED Companion | Integration | HACS | 4.3.2 | https://github.com/zachowj/hass-node-red |", "| ofekashery/vertical-stack-in-card | Frontend | HACS | v1.1.4 | https://github.com/ofekashery/vertical-stack-in-card |", "| piitaya/lovelace-mushroom | Frontend | HACS | v5.2.3 | https://github.com/piitaya/lovelace-mushroom |", "| Playnite Web MQTT | Integration | HACS | 0.0.12 | https://github.com/cvele/playnite_web_mqtt |", "| Remote Home-Assistant | Integration | HACS | 4.6 | https://github.com/custom-components/remote_homeassistant |", "| RomRider/apexcharts-card | Frontend | HACS | v2.2.3 | https://github.com/RomRider/apexcharts-card |", "| SmartIR | Integration | HACS | 1.18.1 | https://github.com/smartHomeHub/SmartIR |", "| Sonoff | Integration | HACS | 3.13.2 | https://github.com/AlexxIT/SonoffLAN |", "| Tapo: Cameras Control | Integration | HACS | 7.2.8 | https://github.com/JurajNyiri/HomeAssistant-Tapo-Control |", "| TCL Home - Unofficial | Integration | HACS | 3.16.0 | https://github.com/nemesa/ha-tcl-home-unofficial-integration |", "| thomasloven/lovelace-auto-entities | Frontend | HACS | v1.16.1 | https://github.com/thomasloven/lovelace-auto-entities |", "| thomasloven/lovelace-card-mod | Frontend | HACS | v4.2.1 | https://github.com/thomasloven/lovelace-card-mod |", "| thomasloven/lovelace-layout-card | Frontend | HACS | v2.4.7 | https://github.com/thomasloven/lovelace-layout-card |", "| thomasloven/lovelace-template-entity-row | Frontend | HACS | v1.4.1 | https://github.com/thomasloven/lovelace-template-entity-row |", "| usernein/tailwindcss-template-card | Frontend | HACS | v3.1.1 | https://github.com/usernein/tailwindcss-template-card |", "| Volkswagen Connect | Integration | HACS | v5.5.1 | https://github.com/robinostlund/homeassistant-volkswagencarnet |", "| VW Group Connect | Integration | HACS | 5.1.1 | https://github.com/its-me-prash/vwgroup-connect-ha |", "| wassy92x/lovelace-digital-clock | Frontend | HACS | v1.2.4 | https://github.com/wassy92x/lovelace-digital-clock |", "| Advanced SSH & Web Terminal | Add-on | Supervisor | 24.1.7 | https://github.com/hassio-addons/app-ssh |", "| deCONZ | Add-on | Supervisor | 8.8.0 | https://github.com/home-assistant/addons/tree/master/deconz |", "| Duck DNS | Add-on | Supervisor | 2.0.1 | https://github.com/home-assistant/addons/tree/master/duckdns |", "| ESPHome Device Builder | Add-on | Supervisor | 2026.10.0 | https://esphome.io/ |", "| Get HACS | Add-on | Supervisor | 1.3.1 | https://github.com/hacs/addons/tree/main/get |", "| Home Assistant Google Drive Backup | Add-on | Supervisor | 0.112.1 | https://github.com/sabeechen/hassio-google-drive-backup |", "| Let's Encrypt | Add-on | Supervisor | 6.5.0 | https://github.com/home-assistant/addons/tree/master/letsencrypt |", "| Mosquitto broker | Add-on | Supervisor | 7.1.2 | https://github.com/home-assistant/addons/tree/master/mosquitto |", "| NGINX Home Assistant SSL proxy | Add-on | Supervisor | 4.5.1 | https://github.com/home-assistant/addons/tree/master/nginx_proxy |", "| Node-RED | Add-on | Supervisor | 22.1.0 | https://github.com/hassio-addons/app-node-red |", "| RPC Shutdown | Add-on | Supervisor | 3.0 | https://github.com/home-assistant/addons/tree/master/rpc_shutdown |", "| Samba share | Add-on | Supervisor | 12.10.0 | https://github.com/home-assistant/addons/tree/master/samba |", "| SQLite Web | Add-on | Supervisor | 6.1.1 | https://github.com/hassio-addons/app-sqlite-web/tree/main/README.md |", "| Studio Code Server | Add-on | Supervisor | 7.2.0 | https://github.com/hassio-addons/app-vscode |", "| TasmoAdmin | Add-on | Supervisor | 0.34.0 | https://github.com/hassio-addons/app-tasmoadmin |", "| TasmoBackup | Add-on | Supervisor | 1.08.00 | https://github.com/danmed/TasmoBackupV1/ |", "| Terminal & SSH | Add-on | Supervisor | 10.5.0 | https://github.com/home-assistant/addons/tree/master/ssh |"] -->

License
----

MIT


**Free Software**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [MQTT]: <https://www.home-assistant.io/integrations/mqtt/>
   [Tasmota]: <https://tasmota.github.io/docs/>
   [deConz]: <https://www.home-assistant.io/integrations/broadlink/>
   [HACS]: <https://hacs.xyz/docs/installation/manual>
   [Broadlink]: <https://www.home-assistant.io/integrations/broadlink/>
