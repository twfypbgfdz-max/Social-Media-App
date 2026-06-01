# Social Media App

Mobile-first Web-App zur lokalen Planung von Social-Media-Ideen und Reels.

## Version

Aktuelle Testversion: `v0.6`

Datei:

`01_APP/tests/social-media-app-v0_6-test.html`

Vorversion:

`01_APP/tests/social-media-app-v0_5-test.html`

Weitere Vorversionen:

`01_APP/tests/social-media-app-v0_4-test.html`

`01_APP/tests/social-media-app-v0_3-test.html`

`01_APP/tests/social-media-app-v0_2-test.html`

`01_APP/tests/social-media-app-v0_1-test.html`

## Funktionen v0.6

- Dashboard mit Gesamtstatus
- Heute-posten-Coach mit konkreter lokaler Posting-Empfehlung
- Empfehlung mit Kategorie, Hook-Typ, Reel-Idee, Hook, CTA, Hashtags und Begruendung
- Empfehlung kann als Idee gespeichert oder in die Pipeline uebernommen werden
- Regelbasierte lokale Logik, keine externe KI/API
- Reel-Ideen-Generator mit lokalen Vorlagen, ohne externe KI/API
- Generator-Kategorien: Push, Pull, Legs, Oberkörper, Arme, Lifestyle, Motivation
- Generierte Ideen koennen direkt als Content-Idee oder Pipeline-Eintrag gespeichert werden
- Content Vault fuer Hooks, Captions, CTAs und Hashtag-Sets
- Vault-Vorlagen speichern, bearbeiten, loeschen, kopieren und uebernehmen
- Neue Content-Ideen koennen Hook, Caption, CTA und Hashtags aus dem Vault uebernehmen
- Content Pipeline mit Status: Idee, Skript, Gefilmt, Geschnitten, Geplant, Hochgeladen
- Pipeline-Uebersicht als Dashboard-Karten
- Erweiterte Dashboard-Statistiken fuer veroeffentlichte Reels
- Erfolgsanalyse mit Top 5 Reels nach Views, Saves und Likes
- Kategorieanalyse mit durchschnittlichen Views, Likes und Saves pro Kategorie
- Hook-Analyse mit Hook-Typen und durchschnittlichen Views
- Dashboard Coach mit Empfehlungen zu Kategorie, Hook-Typ, Saves und Views
- Ideen-Sammlung
- Reel-Planer nach Status
- Statistik-Tracker fuer Reels mit Views, Likes, Kommentaren, Saves, Shares und Followergewinn
- Hook-, Song- und Notizfeld zur Performance-Auswertung
- Screenshot-Upload pro Reel mit lokaler Vorschau
- Lokale Screenshot-Speicherung als Base64, sofern das Bild klein genug ist
- Vorbereiteter Button `Daten aus Screenshot auslesen` ohne Fake-Erkennung
- Kategorien
- Status-System: Idee, Skript, Gefilmt, Geschnitten, Geplant, Hochgeladen
- Lokale Speicherung im Browser via `localStorage`
- Dunkles Premium-Design
- Optimiert fuer iPhone

## Technische Hinweise

- Keine externen Abhaengigkeiten
- Alles in einer HTML-Datei
- Storage-Key: `social-media-app-v0_6`
- v0.5-Daten werden beim ersten Laden der v0.6 moeglichst uebernommen
- OCR/AI ist noch nicht angebunden; Screenshot-Daten werden nicht automatisch ausgelesen
- Keine Verbindung zu Personal-App, Public-App oder Apps-Script
