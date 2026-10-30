# Stundenplan 008

Vollständiges GitHub-Pages-Paket. Alle zehn Dateien im Hauptverzeichnis ersetzen, einschließlich `README.md`.

## Änderungen gegenüber 007

- Kopfzeile ohne Weichzeichner, mit deckendem dunkelblauem Farbverlauf und ohne Textschatten.
- Versionsnummer **V.008** klein und leicht direkt neben „Stundenplan“; sie ist fest im geladenen HTML-Programmcode hinterlegt und zeigt daher die tatsächlich ausgeführte App-Version an.
- Tageskarten auf maximal 82 CSS-Pixel Höhe verkürzt (mindestens 72 Pixel), Zwischenraum 4 Pixel; Schriftgrößen bleiben erhalten. Bei sehr kleinen Displays kann weiterhin gescrollt werden.
- Wochenkarten auf mindestens 76 CSS-Pixel Höhe verdichtet; Schriftgrößen bleiben erhalten.
- Bestehende Echtzeit-Markierung, Heute-Button, Schülerauswahl, Gesten, Offline-Modus und Stundenplandaten unverändert.

## Vollständige Dateiliste

- `index.html` – Oberfläche und Echtzeit-Markierung
- `stundenplaene.json` – Unterrichtsdaten Julia/Carolina
- `app-version.json` – Versionskennung 008
- `sw.js` – Offline-Cache 008
- `manifest.webmanifest` – PWA-Konfiguration
- `icon-180.png` – iPhone-Icon
- `icon-192.png` – PWA-Icon
- `icon-512.png` – PWA-Icon
- `icon-1024.png` – hochauflösendes Icon
- `README.md` – diese Anleitung

Nach dem Hochladen die App online öffnen und bei Bedarf über das Logo aktualisieren. Bei iOS kann ein vollständiges Schließen und erneutes Öffnen der installierten App erforderlich sein, um den neuen Programmcode zu laden.
