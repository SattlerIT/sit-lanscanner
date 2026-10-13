# S-IT LAN Device Scanner

Professioneller LAN- und WLAN-Scanner mit Diagnose, Firewall-Werkzeugen und Performance-Test für Windows.

Entwickelt von **Hans Udo Sattler · Sattler IT-Service, Greifenstein**

Projektseite: https://sattlerit.github.io/sit-lanscanner/

---

## Funktionen

- **Netzwerk-Scan** – erkennt Geräte, Hersteller, Betriebssysteme und offene Ports im LAN und WLAN; eigene Zuordnungen per Rechtsklick
- **Internet-Erreichbarkeit** – prüft DNS, Routing, TCP 443, HTTPS, IPv6 und Browser-Zugriff; dazu Speedtest mit Ping, Download und Upload
- **LAN-Performance** – Live-Durchsatztest mit Schreib- und Leseraten für Netzwerkfreigaben
- **WLAN-Übersicht** – SSID, Signalstärke, Kanal, Frequenzband und Verbindungsraten
- **Netzwerk-Einstellungen** – prüft Netzwerkprofil, Freigaben, SMB-Versionen, Dienste und Firewall-Regeln, mit Reparatur-Funktionen
- **Firewall & Ports** – trägt Ausnahmen für nicht erreichbare Geräte ein und gibt Ports auf diesem PC frei, mit vorheriger Prüfung
- **Log-Manager** – Scans anzeigen, vergleichen und als HTML-Report speichern
- **OUI-Updater** – aktualisiert die Hersteller-Datenbank aus den IEEE-Quellen
- **Skalierbare Oberfläche** – Darstellungsgröße von 90 bis 300 %, unabhängig von der Windows-Skalierung

## Systemanforderungen

- Windows 10 oder Windows 11 (64-Bit)
- Administratorrechte für den vollen Funktionsumfang (ARP-Scan, Netzwerk-Reparatur, Firewall & Ports)
- Npcap empfohlen für erweiterten ARP- und Intensiv-Scan

## Installation

Das Setup (`S-IT-LanScanner-Setup.exe`) installiert das Programm wahlweise:
- **Festplatte** – mit Desktop-Verknüpfung, Startmenü-Eintrag und Eintrag in der Programmliste
- **Portabel** – auf USB-Stick oder in einen eigenen Ordner, ohne Systemeinträge

Bei einem Update bleiben Einstellungen, eigene Zuordnungen, Hersteller-Datenbank und Logs erhalten. Der Deinstaller sichert diese Daten auf Wunsch; bei einer späteren Neuinstallation bietet das Setup an, sie zurückzuholen.

## Download

Aktuelle Version im [Release-Bereich](https://github.com/SattlerIT/sit-lanscanner/releases).

> **Hinweis:** Windows SmartScreen oder Virenscanner können beim ersten Start anschlagen.  
> Dies ist ein bekanntes False Positive bei unabhängig entwickelten Windows-Tools.  
> Alle Dateien stammen ausschließlich von dieser offiziellen GitHub-Seite.

## Erwähnungen

- [CHIP.de – Wertung „Gut“](https://www.chip.de/downloads/S-IT-LAN-Device-Scanner_187223508.html)
- [Deskmodder.de](https://www.deskmodder.de/blog/2026/03/27/s-it-lan-scanner-geraete-im-einen-netzwerk-scannen-und-auflisten/)
- [WinTotal.de](https://www.wintotal.de/download/s-it-lan-device-scanner/)

## Verwendete Komponenten

Das Setup entpackt das Programmarchiv mit der Python-Bibliothek **py7zr** (LGPL-2.1-or-later, https://github.com/miurahr/py7zr). Sie ist zusammen mit weiteren Bibliotheken unverändert in die Setup-EXE eingebunden.

Liste der Komponenten und vollständige Lizenztexte: [S-IT-LanScanner-Setup-3rd-Party-Licenses.txt](https://sattlerit.github.io/sit-lanscanner/S-IT-LanScanner-Setup-3rd-Party-Licenses.txt)

## Lizenz

© 2026 Hans Udo Sattler · Sattler IT-Service, Greifenstein

Lizenzbedingungen: [S-IT-Lizenz.txt](https://sattlerit.github.io/sit-lanscanner/S-IT-Lizenz.txt) · Haftungsausschluss: [Disclaimer.txt](https://sattlerit.github.io/sit-lanscanner/Disclaimer.txt)

## Kontakt

**Sattler IT-Service**  
Hans Udo Sattler · Greifenstein  
tool-entwicklung@sattler-it.de  
http://sattler-it.de
