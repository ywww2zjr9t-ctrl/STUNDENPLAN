# Stundenplan – Version 010

GitHub-Pages-Web-App für Julia (G5B) und Carolina (G7B).

## Neu in Version 010

- Ein Tipp auf das Schullogo prüft sowohl Stundenplandaten als auch die Programmversion.
- Bei einer neuen Programmversion wird der neue Service Worker installiert und aktiviert; anschließend lädt sich die Web-App automatisch neu.
- Nach dem Neuladen prüft die App ihre **im tatsächlich geladenen HTML enthaltene** Versionsnummer. Die Versionsnummer wird niemals nur aufgrund der Server-Metadaten hochgezählt.
- Wenn die automatische Aktivierung oder das Neuladen scheitert, erscheint der Hinweis, die Web-App über den iPhone-App-Umschalter vollständig zu beenden und neu zu starten.
- Ohne neue Programmversion werden nur die Stundenplandaten und die Offline-Dateien aktualisiert.
- Die bisherige Stundenplananzeige, das feste sechsstündige Raster, die Schülerwahl, die Fachfarben und die aktuelle Stundenmarkierung bleiben erhalten.

## Versionskennung

**010** – einheitlich in der sichtbaren App-Anzeige, `index.html` (APP_VERSION), `app-version.json`, `manifest.webmanifest`, Service-Worker-Cache `stundenplan-010`, der Service-Worker-Versionsantwort und diesem README. ZIP: `Stundenplan_010.zip`.

## Wichtiger Hinweis zur Umstellung von 009 auf 010

Version 009 enthält noch die alte Aktualisierungslogik. Beim **ersten Wechsel von 009 auf 010** kann deshalb noch ein vollständiges Schließen und erneutes Öffnen der installierten iPhone-Web-App nötig sein. Erst ab der geladenen Version 010 steht die neue Ein-Tipp-Aktualisierung zur Verfügung. iOS kann die Aktivierung eines Service Workers verzögern; der manuelle Neustart bleibt als Ausweichlösung erhalten.

## GitHub-Upload – alle Dateien ersetzen

- `index.html`
- `stundenplaene.json`
- `app-version.json`
- `sw.js`
- `manifest.webmanifest`
- `icon-180.png`
- `icon-192.png`
- `icon-512.png`
- `icon-1024.png`
- `README.md`

Die Stundenplandaten werden für die Offline-Nutzung lokal gespeichert.
