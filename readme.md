# Advanced Wifi Deauther

A powerful, customizable WiFi Deauther built using the ESP8266 NodeMCU. This tool allows you to audit and test WiFi networks by performing deauthentication and disassociation attacks, beacon flooding, probe spamming, and more.

## Working on:

- ✅ **Deauthentication Attack** — Disconnect clients from any nearby WiFi network.
- ✅ **Disassociation Attack** — Simulate disconnection without affecting router state.
- ✅ **Beacon Flooding** — Spam fake WiFi networks to confuse devices.
- ✅ **Probe Request Spamming** — Flood probe requests with fake SSIDs.
- ✅ **Live Client Scan** — Identify connected devices on WiFi networks in real time.
- ✅ **SSID Cloner** — Clone existing access points to perform Evil Twin attacks.
- ✅ **Web Interface** — Configure attacks through a mobile-friendly web dashboard.
- ✅ **Command Line Interface (Serial)** — Send commands over serial terminal.
- ✅ **Channel Hopper** — Automatically switch between WiFi channels for full coverage.
- ✅ **Custom Attack Scripts** — Run saved scripts for automated multi-step attacks.
- ✅ **Hidden Network Targeting** — Detect and attack hidden SSIDs.
- ✅ **MAC Address Spoofing** — Randomize MAC addresses to avoid detection.
- ✅ **AP Whitelist & Blacklist** — Customize target scope.

## Project Structure:
(to be updated)

``` js
│
├── firmware/
│ ├── main.ino # Main Arduino code
│ ├── attack.h # Attack logic
│ ├── webserver.h # Embedded web dashboard
│ ├── scanner.h # WiFi and client scanner
│ └── settings.h # Configuration options
│
├── tools/
│ ├── script-runner.py # Script automation tool (Python)
│ └── ssid-generator.py # Create fake SSID lists
│
├── docs/
│ └── usage_guide.md
│
└── README.md
```

## Hardware Requirements

- ESP8266 NodeMCU (recommended: ESP-12E/ESP-12F)**
- Power Supply (USB or battery)
- External antenna (optional, for extended range)

## Setting up

### 1. Flash Firmware

```c++
git clone https://github.com/yourusername/esp8266-wifi-deauther.git
cd esp8266-wifi-deauther/firmware
```

