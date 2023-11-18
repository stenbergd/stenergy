# STENergy
Home energy analytics and optimization project

## Hardware
Intel NUC - Mini PC used as automation and control server for STENergy software runtime and data storage
Husdata H60 - Heat pump communication gateway

### Intel NUC Bios Setup
Tested for Intel NUC 13 i5 Pro Kit - Slim (NUC13ANKi50002)

BIOS settings are accessed by pressing F2 during bootup with connected keyboard and screen

To enable BalenaOS to boot, "Secure Boot" has to be disabled in BIOS. Check the Boot menu.

It is also a good idea to make the NUC boot automatically in case of a power failure. To do this, go to Power > Secondary Power Settings and set the setting "After Power Failure" to "Power On"

Press F10 to save and exit BIOS settings.

## Software Stack
MING-based stack for connectivity, data storage, automation logic and visualization
MQTT broker: mosquitto
Telemetry data storage: InfluxDB
Automation logic: Node-RED
Visualization: Grafana
Optimization: TBD
