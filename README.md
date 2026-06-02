# Social Media App

Mobile-first Web-App zur lokalen Planung von Social-Media-Ideen und Reels.

## Version

Aktuelle Testversion: `v0.9.1`

Datei:

`01_APP/tests/social-media-app-v0_9_1-test.html`

Vorversion:

`01_APP/tests/social-media-app-v0_9-test.html`

Weitere Vorversionen:

`01_APP/tests/social-media-app-v0_8-test.html`

`01_APP/tests/social-media-app-v0_7-test.html`

`01_APP/tests/social-media-app-v0_6-test.html`

`01_APP/tests/social-media-app-v0_5-test.html`

`01_APP/tests/social-media-app-v0_4-test.html`

`01_APP/tests/social-media-app-v0_3-test.html`

`01_APP/tests/social-media-app-v0_2-test.html`

`01_APP/tests/social-media-app-v0_1-test.html`

## Funktionen v0.9.1

- iPhone/Safari-Zoom beim Fokussieren von Eingabefeldern verhindert
- `input`, `textarea` und `select` haben mindestens `font-size: 16px`
- Kein `user-scalable=no`, Zoom bleibt nutzerseitig moeglich
- Keine Feature- oder Datenmodell-Aenderung
- Storage-Key bleibt `social-media-app-v0_9`

## Funktionen v0.9

- Clean-MVP-Version ohne neue Kernfeatures
- Keine Demo-Daten, Beispielzahlen oder Fake-Empfehlungen
- Leere Zustaende statt unsicherer Analysen
- Startseite mit drei Aktionen: Neue Idee, Neue Statistik, Pipeline ansehen
- Neue Idee speichern
- Pipeline-Status: Idee, Gefilmt, Geschnitten, Geplant, Hochgeladen
- Neue Reel-Statistik mit Titel, Datum, Kategorie, Views, Likes, Kommentaren, Saves, Shares und Followergewinn
- Einfache Uebersicht mit Anzahl Ideen, geplanten Posts und veroeffentlichten Reels
- Gesamtviews nur bei vorhandenen echten Reel-Statistiken
- Heute-posten-Hinweis nur bei zu wenig Daten; Empfehlung erst ab mehreren gespeicherten Reels
- Generator und Vault bewusst eingeklappt/deaktiviert
- Migration aus v0.8, bekannte Demo-Seeds werden nicht in v0.9 uebernommen
- Ungueltige oder leere Zahlen werden als 0 behandelt
- Statistiken nutzen nur gespeicherte Reel-Daten
- Dunkles Premium-Design mit Gold/Anthrazit
- Mobile-first und ruhiger Desktop-Container

## Funktionen v0.8

- Desktop-UX-Verbesserung ohne neue Kernfeatures
- Breiteres Desktop-Layout mit bis zu ca. 1480px Inhaltsbreite
- Heute-Tab als echtes Dashboard mit Coach, Kacheln und Quick Actions
- Filter-Chips umbrechen auf Desktop statt horizontalem Scrollen
- Kompaktere Listen-/Kartenansicht fuer Ideen, Pipeline, Statistik und Vault
- Ruhigere Vault-Aktionen ueber Details/Aktionsbereich
- Aufgeraeumte UX-Version ohne entfernte Funktionen
- Reduzierte Startseite mit Heute-posten-Coach, Pipeline-Kurzstatus, Top-Empfehlung und Schnellbuttons
- Klare Navigation: Heute, Ideen, Pipeline, Statistik, Vault
- Erweiterte Analysen als einklappbare Details
- Formulare mit sichtbaren Basisfeldern und einklappbaren Mehr Optionen
- Kompaktere Karten mit Details anzeigen
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
- Storage-Key: `social-media-app-v0_9`
- v0.8-Daten werden beim ersten Laden der v0.9 moeglichst uebernommen
- OCR/AI ist noch nicht angebunden; Screenshot-Daten werden nicht automatisch ausgelesen
- Keine Verbindung zu Personal-App, Public-App oder Apps-Script
