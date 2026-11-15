# Super Mac Android Phone Dialer (SMAPD)

Mit SMAPD wählst du auf dem Mac und telefonierst über dein Android-Handy. Die Wähltastatur öffnet auch `tel:`-Links. T9 findet Favoriten, und zu jeder Nummer kannst du Gesprächsergebnisse und Rückruftermine festhalten. Die App hieß bis Version 2.1 **PhonePilot Dial**.

**[SMAPD für macOS herunterladen](https://github.com/Supersynergy/super-mac-android-phone-dialer/releases/latest)**

## Einrichtung

1. Öffne das Disk-Image und ziehe **Super Mac Android Phone Dialer (SMAPD)** nach **Programme**.
2. Öffne **Gerät verbinden** und wähle die entpackten Android SDK Platform-Tools.
3. Verbinde dein Android-Handy per USB und bestätige USB-Debugging auf dem entsperrten Gerät. Bereits mit ADB gekoppeltes WLAN funktioniert ebenfalls.

Die Universal-App unterstützt macOS 13 oder neuer, Apple Silicon und Intel. Deutsch und Englisch sind enthalten. Die App ist ad hoc signiert und hat keine Apple-Notarisierung. Gatekeeper kann den ersten Start blockieren.

## Anrufe und Rückrufe

Unter **Android-Anrufliste** kannst du den Abgleich für ein einzelnes Handy einschalten. SMAPD liest dann die letzten 100 Anrufe des ausgewählten Handys ungefähr jede Minute, solange die App geöffnet ist. Einige Handys sperren den Zugriff. Der Filter **Verpasst** hilft beim Rückruf. Du kannst die Nummer ins Wählfeld laden oder einen Termin vorbereiten. Beim Ausschalten löscht SMAPD die lokale Kopie für dieses Gerät.

**Notizen & Rückrufe** zeigt anstehende Termine nach Fälligkeit. Im Eintragsmenü kannst du eine einzelne Notiz fürs CRM kopieren. Willst du das gesamte Vertriebsjournal auf dem Handy mitnehmen, bestätige die Kopie auf das ausgewählte Gerät. Jede Übertragung ersetzt die lesbare Datei `Documents/SMAPD/Vertriebsjournal.txt` im gemeinsamen Speicher des Handys.

## English

Super Mac Android Phone Dialer lets you dial on your Mac using a connected Android phone. Open telephone links, find T9 favorites and schedule callbacks. Enable the Android call log for each phone separately to see its latest 100 calls and follow up on missed calls. Switching sync off removes that phone’s local copy. To take the complete sales notebook with you, confirm an export from Notes & callbacks. It replaces a plain-text file in the selected phone’s shared Documents folder.

Requires macOS 13 or later and Android SDK Platform-Tools for calls. The download includes a bilingual setup guide. The app is ad hoc signed and has not been notarized by Apple.
