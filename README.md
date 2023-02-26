# Project: PelletMon
[![Build with PlatformIO](https://img.shields.io/badge/build%20with-PlatformIO-orange?logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB3aWR0aD0iMjUwMCIgaGVpZ2h0PSIyNTAwIiB2aWV3Qm94PSIwIDAgMjU2IDI1NiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiBwcmVzZXJ2ZUFzcGVjdFJhdGlvPSJ4TWlkWU1pZCI+PHBhdGggZD0iTTEyOCAwQzkzLjgxIDAgNjEuNjY2IDEzLjMxNCAzNy40OSAzNy40OSAxMy4zMTQgNjEuNjY2IDAgOTMuODEgMCAxMjhjMCAzNC4xOSAxMy4zMTQgNjYuMzM0IDM3LjQ5IDkwLjUxQzYxLjY2NiAyNDIuNjg2IDkzLjgxIDI1NiAxMjggMjU2YzM0LjE5IDAgNjYuMzM0LTEzLjMxNCA5MC41MS0zNy40OUMyNDIuNjg2IDE5NC4zMzQgMjU2IDE2Mi4xOSAyNTYgMTI4YzAtMzQuMTktMTMuMzE0LTY2LjMzNC0zNy40OS05MC41MUMxOTQuMzM0IDEzLjMxNCAxNjIuMTkgMCAxMjggMCIgZmlsbD0iI0ZGN0YwMCIvPjxwYXRoIGQ9Ik0yNDkuMzg2IDEyOGMwIDY3LjA0LTU0LjM0NyAxMjEuMzg2LTEyMS4zODYgMTIxLjM4NkM2MC45NiAyNDkuMzg2IDYuNjEzIDE5NS4wNCA2LjYxMyAxMjggNi42MTMgNjAuOTYgNjAuOTYgNi42MTQgMTI4IDYuNjE0YzY3LjA0IDAgMTIxLjM4NiA1NC4zNDYgMTIxLjM4NiAxMjEuMzg2IiBmaWxsPSIjRkZGIi8+PHBhdGggZD0iTTE2MC44NjkgNzQuMDYybDUuMTQ1LTE4LjUzN2M1LjI2NC0uNDcgOS4zOTItNC44ODYgOS4zOTItMTAuMjczIDAtNS43LTQuNjItMTAuMzItMTAuMzItMTAuMzJzLTEwLjMyIDQuNjItMTAuMzIgMTAuMzJjMCAzLjc1NSAyLjAxMyA3LjAzIDUuMDEgOC44MzdsLTUuMDUgMTguMTk1Yy0xNC40MzctMy42Ny0yNi42MjUtMy4zOS0yNi42MjUtMy4zOWwtMi4yNTggMS4wMXYxNDAuODcybDIuMjU4Ljc1M2MxMy42MTQgMCA3My4xNzctNDEuMTMzIDczLjMyMy04NS4yNyAwLTMxLjYyNC0yMS4wMjMtNDUuODI1LTQwLjU1NS01Mi4xOTd6TTE0Ni41MyAxNjQuOGMtMTEuNjE3LTE4LjU1Ny02LjcwNi02MS43NTEgMjMuNjQzLTY3LjkyNSA4LjMyLTEuMzMzIDE4LjUwOSA0LjEzNCAyMS41MSAxNi4yNzkgNy41ODIgMjUuNzY2LTM3LjAxNSA2MS44NDUtNDUuMTUzIDUxLjY0NnptMTguMjE2LTM5Ljc1MmE5LjM5OSA5LjM5OSAwIDAgMC05LjM5OSA5LjM5OSA5LjM5OSA5LjM5OSAwIDAgMCA5LjQgOS4zOTkgOS4zOTkgOS4zOTkgMCAwIDAgOS4zOTgtOS40IDkuMzk5IDkuMzk5IDAgMCAwLTkuMzk5LTkuMzk4em0yLjgxIDguNjcyYTIuMzc0IDIuMzc0IDAgMSAxIDAtNC43NDkgMi4zNzQgMi4zNzQgMCAwIDEgMCA0Ljc0OXoiIGZpbGw9IiNFNTcyMDAiLz48cGF0aCBkPSJNMTAxLjM3MSA3Mi43MDlsLTUuMDIzLTE4LjkwMWMyLjg3NC0xLjgzMiA0Ljc4Ni01LjA0IDQuNzg2LTguNzAxIDAtNS43LTQuNjItMTAuMzItMTAuMzItMTAuMzItNS42OTkgMC0xMC4zMTkgNC42Mi0xMC4zMTkgMTAuMzIgMCA1LjY4MiA0LjU5MiAxMC4yODkgMTAuMjY3IDEwLjMxN0w5NS44IDc0LjM3OGMtMTkuNjA5IDYuNTEtNDAuODg1IDIwLjc0Mi00MC44ODUgNTEuODguNDM2IDQ1LjAxIDU5LjU3MiA4NS4yNjcgNzMuMTg2IDg1LjI2N1Y2OC44OTJzLTEyLjI1Mi0uMDYyLTI2LjcyOSAzLjgxN3ptMTAuMzk1IDkyLjA5Yy04LjEzOCAxMC4yLTUyLjczNS0yNS44OC00NS4xNTQtNTEuNjQ1IDMuMDAyLTEyLjE0NSAxMy4xOS0xNy42MTIgMjEuNTExLTE2LjI4IDMwLjM1IDYuMTc1IDM1LjI2IDQ5LjM2OSAyMy42NDMgNjcuOTI2em0tMTguODItMzkuNDZhOS4zOTkgOS4zOTkgMCAwIDAtOS4zOTkgOS4zOTggOS4zOTkgOS4zOTkgMCAwIDAgOS40IDkuNCA5LjM5OSA5LjM5OSAwIDAgMCA5LjM5OC05LjQgOS4zOTkgOS4zOTkgMCAwIDAtOS4zOTktOS4zOTl6bS0yLjgxIDguNjcxYTIuMzc0IDIuMzc0IDAgMSAxIDAtNC43NDggMi4zNzQgMi4zNzQgMCAwIDEgMCA0Ljc0OHoiIGZpbGw9IiNGRjdGMDAiLz48L3N2Zz4=)](https://platformio.org/)
[![Based on ksIotFrameworkLib](https://img.shields.io/badge/based%20on-ksIotFrameworkLib-blueviolet)](https://github.com/cziter15/ksIotFrameworkLib)
[![Hits-of-Code](https://hitsofcode.com/github/cziter15/pelletmon?branch=main)](https://hitsofcode.com/github/cziter15/pelletmon/view?branch=main)
[![Device Firmware](https://github.com/cziter15/pelletmon/actions/workflows/main.yml/badge.svg)](https://github.com/cziter15/pelletmon/actions/workflows/main.yml)

## What is it?

This repository contains KiCad PCB design files and firmware for the device called PelletMon(itor).

## Design

This project uses it's own PCB. Hardware design is based on ESP32 (MCU, Wi-Fi, peripherals) and SN65HVD230 (CAN transceiver).
Software is based on Arduino, written in modern C++ and is powered by ksIotFrameworkLib. PlatformIO and VSCode has been selected as IDE.

On early revisions of the boart there are two pins left for HC-SR04 sensor, but due to fuel measurement support in VideNet this hardware feature has been left as unsupported. Feel free to use these pins, keep in mind that there's 5V exposed, not 3.3V.

## Defails about MQTT
After connecting to MQTT broker, device will publish online [ 1 ] / offline [ 0 ] state to /{PREFIX}/connected topic.

| Topic | Direction | Value |
|---|---|---|
| /{PREFIX}/boiler_temp | Device -> Broker | Kettle temperature (float/string eg. 57.1) |
| /{PREFIX}/cwu_temp | Device -> Broker | Hot water temperature (float/string eg. 32.8) |
| /{PREFIX}/burnerusage_total | Device -> Broker | Fuel usage in KG (float/string eg. 3250.0) |
| /{PREFIX}/burnerpower_current | Device -> Broker | Burner power percentage (int/string eg. 30) |
| /{PREFIX}/burnerstatus_current | Device -> Broker | Burner status as index (see below) |
| /{PREFIX}/burner_alarm_active | Device -> Broker | Burner alarm active (int/string, 1 - true, 0 false) |
| /{PREFIX}/controller_enabled | Device -> Broker | Controller active (int/string, 1 - true, 0 false) |
| /{PREFIX}/heatmode_current | Device -> Broker | Heat mode (int/string, see below) |
| /{PREFIX}/hotwatermode_current | Device -> Broker | Hot water mode (int/string, see below) |
| /{PREFIX}/set/controller_enabled | Broker -> Device | Sets controller active (int/string, 1 - true, 0 false) |
| /{PREFIX}/set/hotwatermode | Broker -> Device | Sets hot water mode (int/string, see below) |
| /{PREFIX}/set/heatmode | Broker -> Device | Sets heat mode (int/string, see below) |

### Additional CAN bus link state messages
| Topic | Direction | Value |
|---|---|---|
| /{PREFIX}/num_canbus_req_last_drop | Device -> Broker | Number of CAN requests dropped since last update |
| /{PREFIX}/num_canbus_req_total_drop | Device -> Broker | Total number of CAN requests dropped in current CAN session |

### Hot/Heat water mode (may depend on HMI firmware)
| Value | Mode | Description |
|---|---|---|
| 0 | Off | Disabled |
| 1 | Economic | Economic, reduces fuel usage as defined via HMI |
| 2 | Timer | Time based, will follow schedule as defined via HMI |
| 3 | Comfort | Comfort mode - You'll never get cold again |

### Burner states (may depend on HMI firmware)
| Value | Mode |
|---|---|
| 0 | Turned off / Standby |
| 1 | Ignition |
| 2 | Glowing |
| 3, 4 | N/A |
| 5 | Modulation |
| 6 | Extinguishing |
| 7 | Cleaning |
| 8 | Maintaining |
| 9 | Turned off / Standby |
| 10 | Alarm |

## Known issues

### Hardware

#### rev 0.01a-0.01c
- GPIO0 is directly connected to SWITCH (S1), avoid setting direct HIGH state at that pin from software, because it can result in short circuit when pressing S1, as it will tie IO0 to ground directly. This can damage ESP32 module.
- Due to stability issues R9 resistor on CAN L/H has been removed from final PCB (technically it's now CAN stub and doesn't require additional termination, but keep in mind that CAN L/H wires must be shorter than 30 cm).
#### rev 2.B
- some boards can have swapped CAN H / L on silkscreen
- GPIO0 problem has been eliminated

### Software
- No support for fuel level sensor. (it was previously planned, but VideNet gives info about fuel usage)

## Screenshots and photos
![Installed device](pics/device_setup.png "Installed device")
![HomeAssistant integration](pics/ha_ss.png "HomeAssistant integration")
![PCB render](pics/render.jpg "PCB render")

## Hackaday
Check out project page on Hackaday.io web portal:
https://hackaday.io/project/176557-pelletmon

## Special thanks
- M-Works [ https://m-works.net/ ]
- Robert Labuz.
