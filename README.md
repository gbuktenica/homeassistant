# Installing Home Assistant

## Install Home Assistant OS

### HDD Image

Install instructions

<https://www.home-assistant.io/installation/generic-x86-64/#install-home-assistant-operating-system>

Downloads

<https://www.home-assistant.io/installation/generic-x86-64/>

<https://www.balena.io/etcher>

### Restore Snapshot

1. log on to <http://IP:8123>

1. [USERNAME]\Advanced Mode

1. Supervisor\Add-on Store

1. Click the three dots in the top right

1. Repositories

1. <https://github.com/sabeechen/hassio-google-drive-backup>

1. Refresh Screen

1. Click Repository and click install and start

1. Open Web UI

1. Click Authenticate with Google

1. Copy the string back to Home Assistant

1. Download the Snapshot

1. Restore the Snapshot

## Flash Shelly to ESPHome

1. Flash to ESPHome <https://savjee.be/2020/09/shelly-2.5-flash-esphome-over-the-air/>

URLs are found here: <https://github.com/yaourdt/mgos-to-tasmota>

## Flash Sonoff Mini to ESPHome

### OTA

1. Flash to Tasmota <https://tasmota.github.io/docs/Sonoff-DIY/>

1. Flash to ESPHome using Tasmota <https://esphome.io/guides/migrate_sonoff_tasmota.html>

### Hardwired

1. Use these instructions to wire up <https://acoptex.com/wp/basics-project-109e/>

1. Flash straight to ESPHome (no need for Tasmota)

1. Connect GPIO0 to Ground to enable flash mode.

## Flash Sonoff S26 to ESPHome

<https://www.instructables.com/Home-Automation-Using-the-Sonoff-S26-Smart-Socket/>

1. Load Tasmota via [o2gx](https://github.com/yaourdt/mgos-to-tasmota)

    <http://shellyip/ota?url=http://dl.dasker.eu/firmware/mg2tasmota-Shelly25.zip>
    <http://shellyip/ota?url=http://dl.dasker.eu/firmware/mg2tasmota-Shelly1PM.zip>

1. Connect Tasmota to your network.

1. Load Tasmota minimal via Tasmota.

1. Load ESPHome binary via Tasmota.
