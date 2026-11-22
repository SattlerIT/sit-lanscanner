# S-IT LAN Device Scanner

Network scanner for Windows: finds the devices on your LAN and Wi-Fi, identifies manufacturer, device type and device name, and checks internet reachability, connection quality, Wi-Fi, Windows network settings and firewall. Freeware, in nine languages.

Developed by **Hans Udo Sattler · Sattler IT-Service, Greifenstein, Germany**

Project page: https://sattlerit.github.io/sit-lanscanner/index_en.html · [Deutsche Version](README_DE.md)

![S-IT LAN Device Scanner – device list with device type and device name](https://sattlerit.github.io/sit-lanscanner/Screenshots/liste-en.png)

---

## Features

- **Network scan** – finds devices by ping and ARP and shows IP address, host name, MAC address, manufacturer, operating system and open ports; the ARP scan uses the built-in Windows function
- **Device type and device name** – type from several clues, row colour by type; the "Device name" column shows what a device reports about itself; your own information via right-click
- **Follow-up search for missing devices** – asks known addresses a second time and, optionally, checks typical ports on all silent addresses
- **Wi-Fi profiles** – show saved Wi-Fi networks including passwords, back them up and import them on another PC; comparison of Wi-Fi standards, networks in range, Wi-Fi report as HTML
- **Internet reachability** – DNS, routing, TCP 443, HTTPS, IPv6 and browser access; plus connection path within the LAN and a speed test
- **Domain lookup** – name servers, mail servers and web server of a domain with provider, country and address range
- **Connection quality** – packet loss, response time and jitter to the target and to the gateway, with a rating for telephony and video
- **LAN performance & Wi-Fi** – continuous test for shares and network drives with write and read rate and live chart
- **Network settings** – checks network profile, sharing, SMB versions, services and firewall, with repair functions
- **Firewall & ports** – adds exceptions for unreachable devices and opens ports on this PC, with a check beforehand
- **Logs & reports** – HTML report for each scan, log manager that compares two scans
- **OUI update** – the manufacturer database can be updated within the program from the IEEE sources
- **Nine languages** – Deutsch, English, Nederlands, Español, Français, Italiano, Polski, Hrvatski, Čeština
- **Dark mode and scaling** – 90 to 300 %, independent of the Windows scaling

## System requirements

- Windows 10 or Windows 11 (64-bit)
- Administrator rights for Wi-Fi profiles, network repair and firewall & ports, recommended for the ARP scan
- No additional software

## Installation

The download `sit-lsc-V4-2_latest.zip` contains the setup and the program archive. Please extract the zip completely and start `S-IT-LanScanner-Setup.exe`. The setup offers two ways:

- **Install** – with shortcuts, a Start menu entry and an entry in the list of installed programs
- **Portable** – to a USB stick or a folder of your choice, without system entries

The program is started with `sit-lsc-start.exe`; next to it are the folders Config, Logs, Diag and Help. When updating, settings, your own device information, the manufacturer database and logs are retained. On request, the uninstaller backs up this data; a later installation offers to restore it.

## Download

Current version in the [release section](https://github.com/SattlerIT/sit-lanscanner/releases).

Checksum (SHA-256) of `sit-lsc-V4-2_latest.zip`:

```
797c3a7b9510706e432f5c5d1b79845b840252b784dc0d9c66400741b42b3874
```

To check it in PowerShell, in the folder of the file: `Get-FileHash .\sit-lsc-V4-2_latest.zip`

> **Note:** The program has no purchased signature. Windows SmartScreen or an antivirus program may therefore classify the file as unknown when it is first started. If the checksum matches, the file is unchanged.

## Help

The help is included in the program and can be read online: [English](https://sattlerit.github.io/sit-lanscanner/S-IT-LanScanner-Hilfe_en.html) · [Deutsch](https://sattlerit.github.io/sit-lanscanner/S-IT-LanScanner-Hilfe.html) · more languages on the [project page](https://sattlerit.github.io/sit-lanscanner/index_en.html).

## Mentions

- [CHIP.de – rating "Good"](https://www.chip.de/downloads/S-IT-LAN-Device-Scanner_187223508.html) (German)
- [Deskmodder.de](https://www.deskmodder.de/blog/2026/03/27/s-it-lan-scanner-geraete-im-einen-netzwerk-scannen-und-auflisten/) (German)
- [WinTotal.de](https://www.wintotal.de/download/s-it-lan-device-scanner/) (German)

## Third-party components

The setup extracts the program archive with the Python library **py7zr** (LGPL-2.1-or-later, https://github.com/miurahr/py7zr). It is included unchanged in the setup EXE together with further libraries.

List of components and full licence texts: [S-IT-LanScanner-Setup-3rd-Party-Licenses.txt](https://sattlerit.github.io/sit-lanscanner/S-IT-LanScanner-Setup-3rd-Party-Licenses.txt)

## Licence

© 2026 Hans Udo Sattler · Sattler IT-Service, Greifenstein

Licence and disclaimer in nine languages: [Lizenz-Disclaimer.txt](https://sattlerit.github.io/sit-lanscanner/Lizenz-Disclaimer.txt)

## Contact

**Sattler IT-Service**  
Hans Udo Sattler · Greifenstein, Germany  
tool-entwicklung@sattler-it.de  
http://sattler-it.de
