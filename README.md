# Daily Weather

Eine persönliche, installierbare Wetter-Web-App (PWA).

## Lokal testen
Die Dateien müssen über einen lokalen Webserver oder HTTPS geöffnet werden (Geolocation und PWA benötigen einen sicheren Kontext). Nicht einfach `index.html` per Doppelklick öffnen.

Beispiel mit Python:
```bash
python3 -m http.server 8000
```
Dann `http://localhost:8000` öffnen.

## Online veröffentlichen
Lade den gesamten Inhalt dieses Ordners in ein neues GitHub-Repository und aktiviere GitHub Pages (Settings → Pages → Deploy from a branch → main / root). Danach ist die App über die angezeigte HTTPS-Adresse öffentlich erreichbar.

## Funktionen
- GPS-Standort nach ausdrücklicher Browser-Freigabe
- Suche über Open-Meteo Geocoding
- Aktuelles Wetter, stündliche und 7-Tage-Vorschau
- Temperaturdiagramm, Sonnenzeiten und Wetter-Kennzahlen
- Favoriten lokal im jeweiligen Browser gespeichert
- PWA-Manifest und Service Worker für Installation

Wetterdaten: Open-Meteo. Die App benötigt eine Internetverbindung für aktuelle Wetter- und Geocoding-Daten.
