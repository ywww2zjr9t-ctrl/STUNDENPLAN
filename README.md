# Stundenplan – Version 015

GitHub-Pages-Web-App für Julia (G5B) und Carolina (G7B).

## Neu in Version 015

- Aktive Wochentage in der Wochenansicht sind dunkelblau mit weißer Schrift; an Wochenenden ist kein Wochentag aktiv.
- In der Tagesansicht ist der angezeigte Tag stets dunkelblau mit weißer Schrift.
- Der Heute-Button wird dunkelblau, wenn der tatsächlich heutige Wochentag ausgewählt ist (Montag bis Freitag); ansonsten bleibt er hellblau.
- Die Buttons der Schüler-/Ansichtsauswahl und die Wochentagsnavigation erhalten exakt dieselbe Höhe (mobil 35 CSS-Pixel, größere Bildschirme 40 CSS-Pixel).
- Das gemeinsame Höhenraster bleibt erhalten; Logo und Kopfzeileninhalte bleiben wie in Version 014 gemeinsam um 8 CSS-Pixel nach unten verschoben.
- Die Versionskennung ist in allen relevanten Dateien 015.

## Bewährte Funktionen aus Version 011

- Zwei schmale, durchgehende Pausenbalken in Sandbeige: **09:30–09:45 Uhr** und **11:15–11:25 Uhr**. In der Wochenansicht erstrecken sie sich über alle Spalten, in der Tagesansicht über die gesamte Tagesbreite.
- Laufende Pausen erhalten einen kräftigen sandfarbenen Rahmen; die aktive Unterrichtsstunde behält den Rahmen in der jeweiligen Fachfarbe.
- Während der laufenden Stunde oder Pause füllt sich die Kachel von links nach rechts sanft mit einer etwas kräftigeren Version ihrer Farbe. Der Fortschritt basiert auf der tatsächlichen Gerätezeit und wird sekündlich nachgeführt.
- Schüler, Ansicht **und ausgewählter Wochentag** werden lokal gespeichert und beim nächsten Öffnen wiederhergestellt.
- Das gemeinsame Höhenraster enthält sechs Unterrichtszeilen und zwei schmale Pausenzeilen; Tages- und Wochenansicht behalten dieselben vertikalen Positionen.
- Die automatische Aktualisierung per Schullogo und der manuelle Neustart-Hinweis bei Fehlschlag bleiben erhalten.

## Versionskennung

**015** – einheitlich in der sichtbaren App-Anzeige, `index.html` (APP_VERSION), `app-version.json`, `manifest.webmanifest`, Service-Worker-Cache `stundenplan-015`, der Service-Worker-Versionsantwort und diesem README. ZIP: `Stundenplan_015.zip`.

## Wichtiger Hinweis zur Umstellung von 009 auf 015

Version 009 enthält noch die alte Aktualisierungslogik. Beim **ersten Wechsel von 009 auf 015** kann deshalb noch ein vollständiges Schließen und erneutes Öffnen der installierten iPhone-Web-App nötig sein. Erst ab der geladenen Version 015 steht die neue Ein-Tipp-Aktualisierung zur Verfügung. iOS kann die Aktivierung eines Service Workers verzögern; der manuelle Neustart bleibt als Ausweichlösung erhalten.

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

### Korrektur in Version 015
Das Schullogo wird zusammen mit Titel, Aktualisierungsangabe und Datum/Uhrzeit um 8 CSS-Pixel nach unten verschoben. Die Kopfzeilenhöhe bleibt unverändert.
