![Cyberpunk C64 Command – Neon-Banner](https://raw.githubusercontent.com/breadbin-runner/cyberpunk-c64-command/main/banner.png)

# Cyberpunk C64 Command

**Eine Schaltzentrale für C64 Ultimate und Ultimate 64 auf macOS und Windows.** Disk-Images erkunden, Dateien übertragen, Programme starten, SID-Musik entdecken und sogar eigene Samples auf dem C64 abspielen – alles in einer App mit einem Hauch Neon für die Szene.

Die Disk-Werkstatt funktioniert auch ohne angeschlossenes Gerät. Für Fernsteuerung, Dateiübertragung und Wiedergabe verbindet sich die App direkt mit deinem Ultimate im lokalen Netzwerk. Ein zusätzliches Terminal oder Hilfsprogramm brauchst du dafür nicht.

## Was steckt drin?

| Taste | Bereich | Das kannst du damit tun |
| --- | --- | --- |
| **F1** | Start | Module und Verbindungsstatus im Blick behalten. |
| **F2** | Disk-Werkstatt | D64-, D71- und D81-Images öffnen, Verzeichnisse und Vorschauen ansehen, Dateien sammeln und D64-Arbeitskopien bearbeiten. Mit **Disk Flip** mehrere Images für den Diskwechsel vorbereiten. |
| **F3** | Dateimanager | Dateien und Ordner auf dem Ultimate durchsuchen, übertragen und herunterladen; Images einlegen sowie passende Programme und Musik starten. |
| **F4** | C64-Fernsteuerung | Laufwerke A/B und den C64 steuern, etwa zurücksetzen, anhalten, fortsetzen oder Images einlegen. |
| **F5** | Medienstart | PRG, CRT, SID, MOD und Disk-Images gezielt starten oder abspielen. Bei Disks zwischen schnellem Start und echtem `LOAD` wählen; MOD-Wiedergabe hängt von der Firmware ab. |
| **F6** | Lichtstudio | Gehäuse- und Tastaturbeleuchtung einstellen oder eine der 30 Lichtszenen wählen. |
| **F7** | SID-Sammlung | Eine separat bezogene High Voltage SID Collection durchsuchen, Titel bewerten, eigene SID-Dateien hinzufügen und Stücke auf dem Ultimate abspielen. |
| **F8** | Transferzentrale | Uploads und Downloads mit Fortschritt verfolgen, abbrechen und bei Bedarf erneut versuchen. |
| **F9** | PCM/REU Audio-Studio | WAV-Dateien in 8-Bit-Samples verwandeln, vorhören, als Projekt speichern und mit dem grafischen C64-Player wiedergeben. |
| **F10** | Über diese App | Version, Projektinformationen und Kontakt finden. |

Die Oberfläche gibt es auf **Deutsch und Englisch**. Im **Design Editor** kannst du Farben, Schrift, Anordnung und Details anpassen. Nicht benötigte Module lassen sich in den Einstellungen ausblenden.

## Loslegen

1. Öffne die [Releases](https://github.com/breadbin-runner/cyberpunk-c64-command/releases) und wähle das Paket für **macOS mit Apple Silicon**, **macOS mit Intel-Prozessor** oder den **Windows-64-Bit-Installer**.
2. Auf dem Mac das ZIP entpacken und die App nach „Programme“ bewegen. Unter Windows den Installer starten.
3. Beim ersten Start Sprache und Startansicht wählen. Wenn du einen Ultimate verwenden möchtest, trage seine IP-Adresse oder seinen Hostnamen in den Einstellungen ein und verbinde dich.
4. Für den Dateimanager zusätzlich den FTP-Zugang des Ultimate eintragen. Danach kannst du direkt in der App loslegen.

Für Gerätefunktionen müssen Computer und **C64 Ultimate oder Ultimate 64** im selben erreichbaren Netzwerk sein. Die REST-Schnittstelle des Ultimate muss aktiviert sein; für den Dateimanager wird zusätzlich FTP benötigt. Ohne Ultimate kannst du weiterhin lokale Disk-Images öffnen und D64-Dateien bearbeiten.

## Eigene Sounds auf dem C64

Im PCM/REU Audio-Studio lädst du eine WAV-Datei, wählst einen Ausschnitt und eine Abtastrate, hörst das fertige 8-Bit-Ergebnis vor und speicherst deinen Bearbeitungsstand bei Bedarf als `.pcmstudio`-Projekt. **„Übertragen & abspielen“** schreibt das Sample direkt in die REU und startet den passenden Maschinencode-Player. Auf dem C64 erscheinen Wellenform, Fortschritt, Zeit und bei langen Titeln eine Laufschrift.

Dafür benötigt dein Ultimate **16 MB REU**, **Ultimate Audio mit hörbarer Sampler-Ausgabe** und den **Ultimate DMA Service**. Das Command Interface ist nicht erforderlich. Für einen manuellen Start gibt es ein zusammengehöriges REU+PRG-Paket: Das REU-Abbild muss tatsächlich in die REU geladen werden, bevor du das PRG startest. Das bloße Kopieren auf SD- oder USB-Speicher reicht nicht.

## Anleitung und Austausch

Die App enthält eine ausführliche **deutsche und englische PDF-Anleitung**. Du findest sie über das Zahnrad in der App; sie liegt auch den Programmpaketen bei. Fragen, Ideen und Fehlermeldungen sind unter [GitHub Issues](https://github.com/breadbin-runner/cyberpunk-c64-command/issues) willkommen.

Cyberpunk C64 Command ist ein unabhängiges Fanprojekt für die C64-Community und steht nicht in Verbindung mit Commodore, den Ultimate-Projekten oder der High Voltage SID Collection. Viel Spaß beim Stöbern, Schrauben und Hören! 💾
