# Gravel Dossier — Kike & Robbie

Live-Tracking, Renn-Bilder und Planung für Ultra-Distance-Gravel-Rennen.

## Struktur

```
/
├── index.html          Hub-Startseite (Countdown, Übersicht aller Rennen)
├── shared.css           Gemeinsames Design fürs Hub
├── upload.html           Handy-Upload für Live-Bilder (Cloudinary, ohne Login)
└── badlands-2026/
    └── index.html         Renn-Seite Badlands 2026 (Live-GPS, Galerie, Planung, Fazit)
```

Die 2025er-Seiten (Badlands, Basajaun, Veneto Gravel) liegen weiterhin in ihren eigenen, unveränderten Repos/Ordnern und sind hier nur verlinkt.

## Einrichtung

1. Dieses Repo auf GitHub anlegen, alle Dateien in der Struktur oben hochladen.
2. **Settings → Pages** → Branch `main`, Source `/ (root)` → aktivieren.
3. Erreichbar dann unter `https://<dein-username>.github.io/<repo-name>/`.

## Bild-Upload (Cloudinary)

- Cloud-Name: `c53b7kse`
- Unsigned Preset: `gravel_live`
- „Resource list“-Einstellung ist aktiv → Galerien lesen die getaggten Bilder direkt über `res.cloudinary.com/c53b7kse/image/list/<tag>.json`, kein eigenes Backend nötig.
- Fotos werden in `upload.html` vor dem Senden client-seitig auf max. 1600 px verkleinert (spart mobile Daten im Feld).
- Tags aktuell verfügbar: `badlands2026`, `veneto2026gravel`.

## Offene TODOs für Badlands 2026

- [ ] Live-GPS-Link auf die echte `badlands26`-URL umstellen (aktuell noch `badlands25` als Platzhalter)
- [ ] Komoot-Strecke + Embed-Link einsetzen, sobald final
- [ ] Start-Datum bestätigen (aktuell angenommen: 30.08.2026 · 08:00)
- [ ] Links zu Trainingsplan & Packliste eintragen (aktuell `#`-Platzhalter unten auf der Renn-Seite)
- [ ] Fazit-Sektion nach dem Rennen mit den echten 2026er-Ergebnissen überschreiben (zeigt aktuell noch die 2025er-Zahlen als Referenz)

## Trainingsstand (zuletzt aktualisiert)

FTP 270 W · 72,5 kg · VO₂max 59 · seit Badlands 2025: 12.800 km / 565 h / 52.000 hm / 350.000 kcal

## Kontakt

enrique.doubleyou@gmail.com
