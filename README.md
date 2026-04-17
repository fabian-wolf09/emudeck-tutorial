# EmuDeck Installation
Der Prozess ist eigentlich eh ziemlich straight forward, aber trotzdem hier meine Konfiguration.

## Meine Konfiguration

### Select your Device:
Windows PC

### Pick your level of integration
Low

### ES-DE Default Theme
Escape - Rob Zombie

###  Emulators and tools for Windows PC
Cemu, Dolphin, Azahar, melonDS, Ryujinx

### Emulator and Tools Configurations
Cemu, Dolphin, Azahar, melonDS, Ryujinx, ES-DE

### Configure Aspect Ratio for GameCube games
16:9

## Post-Installation Setup

### Spiele übertragen
Das automatische Öffnen des Emulation Ordners durch EmuDeck hackt noch auf Windows. Aber der Ordner befindet sich immer im Root Ordner der ausgewählten Festplatte am Anfang.

Im Unterordner roms/[die jeweilige Konsole]  kann man dann die Spiele einfach reintransferieren.

:warning: Bei WiiU Spiele den ganzen entpackten Ordner reinkopieren.
:warning: Bei Switch Spiele im Switch Ordner einen eigenen Ordner namens Updates erstellen. Hier kommen die ganzen Updates und DLCs hinein. Die Base Games einfach als einzelne Datei in den switch Ordner.

### Switch-spezifische Extra-Konfigurationen
#### Ryujinx
Dieser Emulator schaut im Gegensatz zu Eden (Schnelligkeit) auf Genauigkeit.

1. In EmuDeck unter Emuatoren verwalten den Emulator installieren/updaten und die Konfiguration reseten/updaten.
2. In *:\Emulation\bios\ryujinx den Firmware-Ordner der aktuellen Version reinziehen (In meinem Google Drive).
3. In *:\Emulation\bios\ryujinx\keys prod.keys und title.keys reintun (In meinem Google Drive).
4. Ryujinx starten und unter Actions Firmware und Keys installieren
5. Unter Options/Settings/Interface Game Directory und DLC/Update Ordner hinzufügen (*:\Emulation\roms\switch & *:\Emulation\roms\switch\updates).

#### Eden
performantere Alternative zu Ryujinx
1. Eden Dateien in C:\Users\fabsw\AppData\Roaming\EmuDeck\Emulators\eden-windows-msvc reinziehen
2. Eden in EmuDeck unter Emulatoren verwalten zurücksetzen.
3. In *:\Emulation\bios\eden den Firmware-Ordner der aktuellsten Version reinziehen (In meinem Google Drive).
4. In *:\Emulation\bios\eden\keys prod.keys und title.keys reintun (In meinem Google Drive).
5. Eden starten und unter Tools Firmware und Keys installieren
6. Unter Emulation/Configure Game Directory und DLC/Update Ordner hinzufügen (*:\Emulation\roms\switch & *:\Emulation\roms\switch\updates).



### Steam ROM Manager
Unter “Emulatoren verwalten” installieren und die Konfiguration updaten.
In der Seitenleiste SRM starten und einrichten
SRM einrichten und bei Parsers alles abwählen bis auf EmulationStation und “Add Games”
Am besten Controller verbinden (Alternativ Pfeiltasten und Enter)
In Steam EmulationStationDE starten (Vorraussetzung ist min. 1 ROM)

### ES-DE
1. In ES-DE in Settings den Scraper einmal durchlaufen lassen
2. Unter Other Settings/Alternative Emulator den richtigen Emulator auswählen
