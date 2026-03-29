# Hoymiles MQTT Add-on for Home Assistant

This add-on reads Hoymiles DTU-Pro-S via Modbus TCP and publishes inverter
data to MQTT (compatible with Home Assistant MQTT auto-discovery).

## Features
- Fast refresh (5 seconds or user-defined)
- Local Modbus TCP (DTU-Pro-S supported)
- MQTT auto-discovery for HA
- Cloud Hoymiles NOT impacted (local read only)

## Configuration
The add-on uses the following configurable options:
- `dtu_host` (IP of your DTU-Pro-S)
- `dtu_port`
- `query_period`
- `mqtt_host`
- `mqtt_user`
- `mqtt_pass`

After starting the add-on, inverter data appears in Home Assistant under MQTT entities.
