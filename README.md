CatSniffer is an original multiprotocol, and multiband board made for sniffing, communicating, and attacking IoT (Internet of Things) devices. It was designed as a highly portable USB stick that integrates the new chips TI CC1352, Semtech SX1262, and an RP2040 for V3 or a Microchip SAMD21E17 for V2.

This board is a swiss army knife for IoT security researchers, developers, and enthusiasts. The board can be used with different types of software including third-party sniffers such as SmartRF Packet Sniffer, Sniffle, zigbee2mqtt, Z-Stack-firmware, Ubiqua Protocol Analyzer, our custom software, or you can even write your own software for your specific needs.

CatSniffer can operate in 3 different technologies:

LoRa
Sub 1 GHz
2.4 GHz
This work was inspired by our friend's work Michael Ossmann as a tribute to his outstanding job in Greatscott Gadgets, making devices like the YardStick, GreatFET, HackRF, and Ubertooth.


Versions
The CatSniffer has been evolving since its first release:

CatSniffer v1.2
CatSniffer v1.3
CatSniffer v2.0
CatSniffer v2.1
CatSniffer v3.1
We as an pro-open-source companies decided to keep the support for each version, but having in mind that newer versions will have more features than the first versions.

The different firmwares are inside the repository and not in the realese section to keep a propper track of the compiled and source files.

Protocols
Thread
Zigbee
Bluetooth 5 Low Energy (BLE)
IEEE 
6LoWPAN (IPv6 over Low power Wireless Personal Area Networks)
Sub 1Ghz and patented systems
LoRa/LoRaWAN
Wi-SUN
Amazon Sidewalk
mioty®
Features
"The SimpleLink™ CC1352P1F3RGZ device is a multiprotocol and multi-band Sub-1 GHz and 2.4-GHz wireless microcontroller (MCU) supporting Thread, Zigbee®, Bluetooth® 5.2 Low Energy, IEEE 802.15.4g, IPv6-enabled smart objects (6LoWPAN), MIOTY®, Wi-SUN®, proprietary systems".
CatSniffer uses Microchip SAMD21E17 (V2 or previous) and RP2040 (V3 or later) as a USB-UART bridge to communicate with the CC1352 chip; it's not necessary for a manual driver installation (exceptions could exist).
Compatible OS: Windows and Linux.
Auto program through the bootloader from TI CC (as long as it's not disabled in the code). No need for an external programmer, and it can be debugged with cJTAG through the default pin.
Antenna SMA port for an Antenna of your choice.
LEDs of general-purpose.
Reset button for RP2040, SAMD21 & CC1352, Boot of CC1352, and one more for general purpose.
Wiki and Getting Started
Getting Started in our Wiki









