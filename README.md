# Stundenplan – Version 011

GitHub-Pages-Web-App für Julia (G5B) und Carolina (G7B).

## Neu in Version 011

- Zwei schmale, durchgehende Pausenbalken in Sandbeige: **09:30–09:45 Uhr** und **11:15–11:25 Uhr**. In der Wochenansicht erstrecken sie sich über alle Spalten, in der Tagesansicht über die gesamte Tagesbreite.
- Laufende Pausen erhalten einen kräftigen sandfarbenen Rahmen; die aktive Unterrichtsstunde behält den Rahmen in der jeweiligen Fachfarbe.
- Während der laufenden Stunde oder Pause füllt sich die Kachel von links nach rechts sanft mit einer etwas kräftigeren Version ihrer Farbe. Der Fortschritt basiert auf der tatsächlichen Gerätezeit und wird sekündlich nachgeführt.
- Schüler, Ansicht **und ausgewählter Wochentag** werden lokal gespeichert und beim nächsten Öffnen wiederhergestellt.
- Das gemeinsame Höhenraster enthält sechs Unterrichtszeilen und zwei schmale Pausenzeilen; Tages- und Wochenansicht behalten dieselben vertikalen Positionen.
- Die automatische Aktualisierung per Schullogo und der manuelle Neustart-Hinweis bei Fehlschlag bleiben erhalten.

## Versionskennung

**011** – einheitlich in der sichtbaren App-Anzeige, `index.html` (APP_VERSION), `app-version.json`, `manifest.webmanifest`, Service-Worker-Cache `stundenplan-011`, der Service-Worker-Versionsantwort und diesem README. ZIP: `Stundenplan_011.zip`.

## Wichtiger Hinweis zur Umstellung von 009 auf 011

Version 009 enthält noch die alte Aktualisierungslogik. Beim **ersten Wechsel von 009 auf 011** kann deshalb noch ein vollständiges Schließen und erneutes Öffnen der installierten iPhone-Web-App nötig sein. Erst ab der geladenen Version 011 steht die neue Ein-Tipp-Aktualisierung zur Verfügung. iOS kann die Aktivierung eines Service Workers verzögern; der manuelle Neustart bleibt als Ausweichlösung erhalten.

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
