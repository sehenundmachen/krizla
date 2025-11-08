# mocracy.de

**Live Timeline für öffentlich-rechtliche Nachrichten, Talkshows & Kommentare**

Eine moderne Web-Plattform zur Live-Ansicht und Dokumentation von Sendungen öffentlich-rechtlicher Sender aus dem deutschsprachigen Raum.

## Features

### Aktuell implementiert:

- **Waipu TV-Style Timeline**: Multi-Row Layout mit einem Sender pro Zeile
- **15 Sender Support**:
  - ARD, tagesschau, ZDF, Phoenix, Arte, 3sat
  - BR, WDR, NDR, SWR, HR, MDR, RBB
  - ZDFinfo, tagesschau24
- **Zeitachse**: Horizontale Timeline mit Zeitmarkierungen (alle 30 Min)
- **Program-Bubbles**: Länge entspricht Sendungsdauer (wie in Musikprogrammen)
- **Live-Line**: Rote Linie zeigt aktuelle Zeit an
- **Kategorien-Filter**:
  - Nachrichten
  - Talkshows
  - Kommentare & Meinung
  - Dokumentationen
  - Politik
- **Live-Erkennung**: Echtzeit-Anzeige aktuell laufender Sendungen
- **Zoom-Funktion**: Skalierbare Timeline (50% - 200%)
- **Sticky Labels**: Sender-Namen bleiben beim Scrollen sichtbar
- **Click-Details**: Tooltip mit erweiterten Infos beim Klick
- **Video-Integration**: Direkter Zugriff auf Mediathek-Videos
- **Auto-Refresh**: Automatische Aktualisierung alle 5 Minuten
- **YouTube-Ready**: Channel IDs für Tagesschau, ZDF, Phoenix vorbereitet

## Technologie

### API:
- **MediathekViewWeb API** - Aggregator für öffentlich-rechtliche Mediatheken
  - ARD Mediathek
  - ZDF Mediathek
  - Arte
  - Phoenix
  - 3sat
  - ORF (Österreich)
  - SRF (Schweiz)

### Frontend:
- Pure HTML5/CSS3/JavaScript
- Keine Frameworks notwendig
- Responsive Design
- Modern Dark Theme

## Geplante Features

- [ ] YouTube-Integration aktivieren (API Key benötigt)
  - Videos von Tagesschau, ZDF heute, Phoenix in Timeline
  - Sortierung nach Veröffentlichungszeit zusammen mit TV
- [ ] User-Login System
- [ ] Kommentar-Funktion für Sendungen
- [ ] Persistente Bewertungen & Stimmungsbarometer
- [ ] Video-Player Integration (statt externe Links)
- [ ] Such-Funktion über alle Sendungen
- [ ] Favoriten/Watchlist
- [ ] Share-Funktionalität
- [ ] Push-Benachrichtigungen für favorisierte Sendungen
- [ ] Statistiken & Trends zu Sendungen
- [ ] Backend-API für User-Daten
- [ ] Weitere Sender: ORF (Österreich), SRF (Schweiz)
- [ ] Export-Funktion für Timeline

## Installation

1. Repository klonen
2. `index.html` in Browser öffnen
3. Fertig! Keine Dependencies erforderlich

## Nutzung

- **Kategorien wählen**: Klicke auf die Filter-Buttons oben
- **Timeline navigieren**: Horizontal und vertikal scrollen
- **Zoom**: +/- Buttons rechts oben (50% - 200%)
- **Details anzeigen**: Klick auf Sendung öffnet Tooltip
- **Live-Sendungen**: Rote Markierung + LIVE Badge
- **Zeitachse**: Zeitmarkierungen alle 30 Minuten
- **NOW-Line**: Rote Linie zeigt aktuelle Zeit
- **Video abspielen**: "Abspielen" Button im Tooltip
- **Sender-Rows**: Jeder Sender hat eigene Zeile (wie Waipu TV)

## Legal

- Alle Inhalte stammen von öffentlich-rechtlichen Sendern
- Verwendung der MediathekViewWeb API (Open Source)
- Keine Downloads, nur Streaming-Links
- Keine Urheberrechtsverletzungen

## Lizenz

Open Source - für Bildungszwecke und öffentliche Dokumentation

## Kontakt

Projekt: mocracy.de - Democracy through Media Transparency
