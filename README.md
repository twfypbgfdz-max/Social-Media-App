# Social Media App

Mobile-first Web-App zur lokalen Planung von Social-Media-Ideen und Reels.

## Version

Aktuelle Testversion: `v0.3`

Datei:

`01_APP/tests/social-media-app-v0_3-test.html`

Vorversion:

`01_APP/tests/social-media-app-v0_2-test.html`

Weitere Vorversion:

`01_APP/tests/social-media-app-v0_1-test.html`

## Funktionen v0.3

- Dashboard mit Gesamtstatus
- Erweiterte Dashboard-Statistiken fuer veroeffentlichte Reels
- Ideen-Sammlung
- Reel-Planer nach Status
- Statistik-Tracker fuer Reels mit Views, Likes, Kommentaren, Saves, Shares und Followergewinn
- Hook-, Song- und Notizfeld zur Performance-Auswertung
- Screenshot-Upload pro Reel mit lokaler Vorschau
- Lokale Screenshot-Speicherung als Base64, sofern das Bild klein genug ist
- Vorbereiteter Button `Daten aus Screenshot auslesen` ohne Fake-Erkennung
- Kategorien
- Status-System: Idee, Gefilmt, Geschnitten, Hochgeladen
- Lokale Speicherung im Browser via `localStorage`
- Dunkles Premium-Design
- Optimiert fuer iPhone

## Technische Hinweise

- Keine externen Abhaengigkeiten
- Alles in einer HTML-Datei
- Storage-Key: `social-media-app-v0_3`
- v0.2-Daten werden beim ersten Laden der v0.3 moeglichst uebernommen
- OCR/AI ist noch nicht angebunden; Screenshot-Daten werden nicht automatisch ausgelesen
- Keine Verbindung zu Personal-App, Public-App oder Apps-Script
