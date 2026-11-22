# S-IT LAN Device Scanner

Netzwerk-Scanner für Windows: findet die Geräte im LAN und WLAN, erkennt Hersteller, Gerätetyp und Gerätename und prüft Internet-Erreichbarkeit, Verbindungsqualität, WLAN, Windows-Netzwerkeinstellungen und Firewall. Freeware, in neun Sprachen.

Entwickelt von **Hans Udo Sattler · Sattler IT-Service, Greifenstein**

Projektseite: https://sattlerit.github.io/sit-lanscanner/ · [English version](README.md)

![S-IT LAN Device Scanner – Geräteliste mit Gerätetyp und Gerätename](https://sattlerit.github.io/sit-lanscanner/Screenshots/liste-de.png)

---

## Funktionen

- **Netzwerk-Scan** – findet Geräte per Ping und ARP und zeigt IP-Adresse, Hostname, MAC-Adresse, Hersteller, Betriebssystem und offene Ports; der ARP-Scan nutzt die eingebaute Funktion von Windows
- **Gerätetyp und Gerätename** – Typ aus mehreren Hinweisen, Zeilenfarbe nach Typ; die Spalte „Gerätename“ zeigt, was ein Gerät selbst meldet; eigene Angaben per Rechtsklick
- **Nachsuche für fehlende Geräte** – fragt bekannte Adressen ein zweites Mal und auf Wunsch typische Ports bei allen stillen Adressen ab
- **WLAN-Profile** – gespeicherte WLANs samt Passwort anzeigen, sichern und auf einem anderen PC einspielen; Vergleich der WLAN-Standards, WLANs in Reichweite, WLAN-Bericht als HTML
- **Internet-Erreichbarkeit** – DNS, Routing, TCP 443, HTTPS, IPv6 und Browser-Zugriff; dazu Verbindungsweg im LAN und Geschwindigkeitstest
- **Domain-Auskunft** – Nameserver, Mailserver und Webserver einer Domain mit Anbieter, Land und Adressbereich
- **Verbindungsqualität** – Paketverlust, Antwortzeit und Schwankung zum Ziel und zum Gateway, mit Bewertung für Telefonie und Video
- **LAN-Performance & WLAN** – Dauertest für Freigaben und Netzlaufwerke mit Schreib- und Leserate und Live-Kurve
- **Netzwerk-Einstellungen** – prüft Netzwerkprofil, Freigaben, SMB-Versionen, Dienste und Firewall, mit Reparatur-Funktionen
- **Firewall & Ports** – trägt Ausnahmen für nicht erreichbare Geräte ein und gibt Ports auf diesem PC frei, mit vorheriger Prüfung
- **Logs & Reports** – HTML-Report je Scan, Log-Manager mit Vergleich zweier Scans
- **OUI-Update** – die Hersteller-Datenbank lässt sich im Programm aus den Quellen der IEEE aktualisieren
- **Neun Sprachen** – Deutsch, English, Nederlands, Español, Français, Italiano, Polski, Hrvatski, Čeština
- **Dunkle Darstellung und Skalierung** – 90 bis 300 %, unabhängig von der Windows-Skalierung

## Systemanforderungen

- Windows 10 oder Windows 11 (64-Bit)
- Administratorrechte für WLAN-Profile, Netzwerk-Reparatur und Firewall & Ports, empfohlen für den ARP-Scan
- Keine Zusatzsoftware

## Installation

Der Download `sit-lsc-V4-2_latest.zip` enthält das Setup und das Programmarchiv. Bitte die Zip vollständig entpacken und `S-IT-LanScanner-Setup.exe` starten. Das Setup installiert das Programm wahlweise:

- **Installieren** – mit Verknüpfungen, Startmenü-Eintrag und Eintrag in der Programmliste
- **Portabel** – auf einen USB-Stick oder in einen eigenen Ordner, ohne Systemeinträge

Gestartet wird über `sit-lsc-start.exe`; daneben liegen die Ordner Config, Logs, Diag und Help. Bei einem Update bleiben Einstellungen, eigene Angaben, Hersteller-Datenbank und Logs erhalten. Der Deinstaller sichert diese Daten auf Wunsch; eine spätere Neuinstallation bietet an, sie zurückzuholen.

## Download

Aktuelle Version im [Release-Bereich](https://github.com/SattlerIT/sit-lanscanner/releases).

Prüfsumme (SHA-256) von `sit-lsc-V4-2_latest.zip`:

```
797c3a7b9510706e432f5c5d1b79845b840252b784dc0d9c66400741b42b3874
```

Prüfen in der PowerShell, im Ordner der Datei: `Get-FileHash .\sit-lsc-V4-2_latest.zip`

> **Hinweis:** Das Programm hat keine gekaufte Signatur. Windows SmartScreen oder ein Virenscanner stufen die Datei beim ersten Start deshalb mitunter als unbekannt ein. Stimmt die Prüfsumme, ist die Datei unverändert.

## Hilfe

Die Hilfe ist im Programm enthalten und online lesbar: [Deutsch](https://sattlerit.github.io/sit-lanscanner/S-IT-LanScanner-Hilfe.html) · [English](https://sattlerit.github.io/sit-lanscanner/S-IT-LanScanner-Hilfe_en.html) · weitere Sprachen auf der [Projektseite](https://sattlerit.github.io/sit-lanscanner/).

## Erwähnungen

- [CHIP.de – Wertung „Gut“](https://www.chip.de/downloads/S-IT-LAN-Device-Scanner_187223508.html)
- [Deskmodder.de](https://www.deskmodder.de/blog/2026/03/27/s-it-lan-scanner-geraete-im-einen-netzwerk-scannen-und-auflisten/)
- [WinTotal.de](https://www.wintotal.de/download/s-it-lan-device-scanner/)

## Verwendete Komponenten

Das Setup entpackt das Programmarchiv mit der Python-Bibliothek **py7zr** (LGPL-2.1-or-later, https://github.com/miurahr/py7zr). Sie ist zusammen mit weiteren Bibliotheken unverändert in die Setup-EXE eingebunden.

Liste der Komponenten und vollständige Lizenztexte: [S-IT-LanScanner-Setup-3rd-Party-Licenses.txt](https://sattlerit.github.io/sit-lanscanner/S-IT-LanScanner-Setup-3rd-Party-Licenses.txt)

## Lizenz

© 2026 Hans Udo Sattler · Sattler IT-Service, Greifenstein

Lizenz und Haftungsausschluss in neun Sprachen: [Lizenz-Disclaimer.txt](https://sattlerit.github.io/sit-lanscanner/Lizenz-Disclaimer.txt)

## Kontakt

**Sattler IT-Service**  
Hans Udo Sattler · Greifenstein  
tool-entwicklung@sattler-it.de  
http://sattler-it.de
