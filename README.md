# **CatSniffer**

## Overview

CatSniffer 😼 is a multiprotocol, multiband device designed for sniffing, communicating, and attacking IoT (Internet of Things) devices. Shaped as a highly portable USB stick, it integrates powerful chips like **TI CC1352**, **Semtech SX1262**, and either the **RP2040** (for V3 and newer) or **Microchip SAMD21E17** (for V2 and earlier).

This device serves as a comprehensive tool for IoT security researchers, developers, and enthusiasts. CatSniffer is compatible with a wide range of software, including:

- SmartRF Packet Sniffer
- Sniffle
- zigbee2mqtt
- Z-Stack-firmware
- Ubiqua Protocol Analyzer
- Custom applications tailored to your specific needs

---

## Supported Technologies

CatSniffer can operate across multiple protocols:
- **LoRa**
- **Sub-1 GHz**
- **2.4 GHz**

Inspired by the work of Michael Ossmann and tools like the YardStick, GreatFET, HackRF, and Ubertooth, CatSniffer pays homage to the open-source hardware community.

---

## Versions

CatSniffer has evolved through several iterations, each improving on the previous:
- **CatSniffer v1.2**
- **CatSniffer v1.3**
- **CatSniffer v2.0**
- **CatSniffer v2.1**
- **CatSniffer v3.1**

All versions are supported, but newer versions include additional features and enhancements. Firmware for each version is tracked separately within the repository for clarity and ease of access.

---

## Protocols Supported

CatSniffer is compatible with the following protocols:
- **Thread**
- **Zigbee**
- **Bluetooth 5 Low Energy (BLE)**
- **IEEE 802.15.4g**
- **6LoWPAN**
- **LoRa/LoRaWAN**
- **Wi-SUN**
- **Amazon Sidewalk**
- **mioty®**

---

## Features

- **Multiprotocol and Multi-Band:** Operates across LoRa, Sub-1 GHz, and 2.4 GHz frequencies.
- **Auto Programming:** Integrated bootloader from TI CC; no external programmer needed.
- **User-Friendly Design:** Includes LEDs for status, reset buttons, and a general-purpose button.
- **Customizable:** SMA port for antenna selection and support for custom firmware or software development.
- **Cross-Platform Compatibility:** Works with Windows and Linux.

---

## Repositories

- **Firmware:** [CatSniffer Firmware Repository](https://github.com/ElectronicCats/CatSniffer-Firmware)
- **Software:** [CatSniffer Tools Repository](https://github.com/ElectronicCats/CatSniffer-Tools)

---

## Compatible Software

CatSniffer works with multiple software tools for sniffing and debugging:
- **Smart RF Packet Sniffer 2**
- **Wireshark**
- **Sniffle**
- **zigbee2mqtt**
- **Z-Stack-firmware**
- **pycatsniffer** (Beta)
- **Ubiqua Protocol Analyzer**

---

## Pre-requisites for Building Firmware

- **IDE:** Arduino IDE for RP2040 or SAMD21E17
- **Compiler:** Code Composer Studio (tested with CCS 10.2)
- **SDK:** SimpleLink CC13x2 and CC26x2 SDK
- **Programming Language:** Python 3

---


## License


- **Firmware License:** Released under a **GNU AGPL v3.0** license. See the `LICENSE` file for more information.
- **Hardware License:** Released under a **CERN Open Hardware Licence v1.2**. See the `LICENSE_HARDWARE` file for more details.


---

