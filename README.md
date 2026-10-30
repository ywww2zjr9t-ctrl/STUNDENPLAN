# Stundenplan 007

Vollständiges GitHub-Pages-Paket mit zehn Dateien. **Alle Dateien im Hauptverzeichnis des vorhandenen Repositorys ersetzen, einschließlich `README.md`.**

## Neu in Version 007

Die aktuell laufende Stunde erhält in Wochen- und Tagesansicht einen feinen, 2 Pixel breiten Rahmen in der kräftigen Farbe des jeweiligen Unterrichtsfachs. Die Kachelfarbe und Schriftgröße bleiben unverändert. Die Markierung erscheint nur am tatsächlichen Wochentag und nur während des exakten Zeitintervalls der Unterrichtsstunde. Pausen, Zeiten vor/nach Unterricht und Wochenenden bleiben unmarkiert. Beim Wechsel zur nächsten Stunde wird die Markierung automatisch aktualisiert, auch offline. Bei Rückkehr aus dem Hintergrund wird die Zeit sofort neu geprüft. In der Tagesansicht erscheint die Markierung nur, wenn der heutige Tag angezeigt wird.

Alle Funktionen von 006 bleiben erhalten (Heute-Button, kompakte Tageskarten, Langnamen, Französisch J207, Animationen, Offline-Speicherung, Aktualisierung per Logo und Herunterziehen).

## Vollständige Dateiliste

- `index.html` – Oberfläche und Echtzeit-Markierung
- `stundenplaene.json` – Unterrichtsdaten Julia/Carolina
- `app-version.json` – Versionskennung 007
- `sw.js` – Offline-Cache 007
- `manifest.webmanifest` – PWA-Konfiguration
- `icon-180.png` – iPhone-Icon
- `icon-192.png` – PWA-Icon
- `icon-512.png` – PWA-Icon
- `icon-1024.png` – hochauflösendes Icon
- `README.md` – diese Anleitung

Nach dem Hochladen die App online öffnen und bei Bedarf über das Logo aktualisieren. Bei iOS kann ein vollständiges Schließen und erneutes Öffnen der installierten App erforderlich sein, um den neuen Programmcode zu laden.
