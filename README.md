# ESP32 CAN Sniffer

Windows desktop CAN bus sniffer & reverse-engineering tool for **ESP32 + MCP2518FD** — not an OBD-II scanner. It taps the CAN bus directly, so it decodes *everything* the bus broadcasts, not just the gateway-filtered slice an OBD port exposes.

🔗 **[esp32canbus.pages.dev](https://esp32canbus.pages.dev/)** — full details, screenshots, and downloads

![Dashboard](https://esp32canbus.pages.dev/images/dashboard.png)

## What it does

- Live CAN monitoring over USB serial or Wi-Fi (ESP32 + MCP2518FD)
- Signal-level decoding (units, scaling, enums) — not just raw hex bytes
- **Compare tab**: freeze a baseline, then see exactly which ID and byte changed as you flip a switch in the car
- DBC import/export
- Session save / load / replay (streaming, unlimited length)
- Optional reverse-engineered **FIAT dictionary add-on** (hundreds of decoded signals across C-CAN and B-CAN)

## Get it

- **Free 7-day demo**: [Download the installer](https://github.com/esp32support/esp32-can-sniffer/releases/latest/download/ESP32_CAN_Sniffer_Setup.exe) — the installer isn't signed with a commercial certificate yet, so Windows SmartScreen may prompt; see the [FAQ](https://esp32canbus.pages.dev/docs/faq.html) if you hit it
- **PRO license / FIAT dictionary add-on**: [esp32canbus.pages.dev/purchase.html](https://esp32canbus.pages.dev/purchase.html)
- **Hardware**: any ESP32 + MCP2518FD module (~€10 on AliExpress) — no custom PCB needed

## Docs

- [User manual](https://esp32canbus.pages.dev/docs/user_manual.html)
- [FAQ](https://esp32canbus.pages.dev/docs/faq.html)
- [About](https://esp32canbus.pages.dev/docs/about.html)

---

This repository hosts Windows installer releases only. The application is closed-source, developed by **IFIX ELEKTRONIKA**.
