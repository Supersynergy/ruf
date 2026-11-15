# Ruf

**Vom Mac über dein Android-Handy anrufen**

Ein Telefonlink in einer E-Mail oder im CRM lädt die Nummer ins Wählfeld von Ruf. Du kannst die Nummer auch eintippen. Mit **Anrufen** startest du das Gespräch auf deinem verbundenen Android-Handy. Ruf wird von Supersynergy entwickelt. Das Gespräch führst du am Handy oder über dessen Headset.

**[Ruf für macOS herunterladen](https://github.com/Supersynergy/super-mac-android-phone-dialer/releases/latest)**

Frühere Namen sind **Super Mac Android Phone Dialer (SMAPD)** und **PhonePilot Dial**. Beim Update verwendet Ruf dieselben lokalen Favoriten, Rückrufnotizen und Einstellungen für Telefonlinks.

## Einrichtung

1. Öffne das Disk-Image und ziehe **Ruf (Supersynergy)** nach **Programme**.
2. Öffne **Gerät verbinden** und wähle die entpackten Android SDK Platform-Tools.
3. Verbinde dein Android-Handy per USB und bestätige USB-Debugging auf dem entsperrten Gerät. Bereits mit ADB gekoppeltes WLAN funktioniert ebenfalls.
4. Damit Ruf Telefonlinks öffnet, wähle unter **Gerät verbinden** die Option **Für Telefonlinks als Standard setzen**.

Die Universal-App unterstützt macOS 13 oder neuer, Apple Silicon und Intel. Deutsch und Englisch sind enthalten. Die App ist ad hoc signiert und hat keine Apple-Notarisierung. Gatekeeper kann den ersten Start blockieren.

## Anrufe und Rückrufe

Unter **Android-Anrufliste** kannst du den Abgleich für ein einzelnes Handy einschalten. Ruf liest dann die letzten 100 Anrufe des ausgewählten Handys ungefähr jede Minute, solange die App geöffnet ist. Einige Handys sperren den Zugriff. Der Filter **Verpasst** hilft beim Rückruf. Du kannst die Nummer ins Wählfeld laden oder einen Termin vorbereiten. Beim Ausschalten löscht Ruf die lokale Kopie für dieses Gerät.

**Notizen & Rückrufe** zeigt anstehende Termine nach Fälligkeit. Im Eintragsmenü kannst du eine einzelne Notiz fürs CRM kopieren. Willst du das gesamte Vertriebsjournal auf dem Handy mitnehmen, bestätige die Kopie auf das ausgewählte Gerät. Jede Übertragung ersetzt die lesbare Datei `Documents/SMAPD/Vertriebsjournal.txt` im gemeinsamen Speicher des Handys.

## English

Ruf by Supersynergy is an Android dialer for macOS. Dial on your Mac and speak on your connected Android phone or its headset. Open telephone links, find T9 favorites and schedule callbacks. Enable the Android call log for each phone separately to see its latest 100 calls and follow up on missed calls. Switching sync off removes that phone’s local copy. To take the complete sales notebook with you, confirm an export from Notes & callbacks. It replaces a plain-text file in the selected phone’s shared Documents folder.

Requires macOS 13 or later and Android SDK Platform-Tools for calls. The download includes a bilingual setup guide. The app is ad hoc signed and has not been notarized by Apple.
