# mocracy.de

**Live Timeline für öffentlich-rechtliche Nachrichten, Talkshows & Kommentare**

Eine moderne Web-Plattform zur Live-Ansicht und Dokumentation von Sendungen öffentlich-rechtlicher Sender aus dem deutschsprachigen Raum.

## Features

### Aktuell implementiert:

#### Timeline & Layout
- **Waipu TV-Style Timeline**: Multi-Row Layout - ein Sender pro Zeile
- **17 Sender Support**:
  - ARD, tagesschau, ZDF, Phoenix, Arte, 3sat
  - BR, WDR, NDR, SWR, HR, MDR, RBB, SR
  - DW (Deutsche Welle), ZDFinfo, tagesschau24
- **Program-Bubbles**: Länge = Sendungsdauer (wie Soundbars in DAWs)
- **Zeitraster**: Gestrichelte Linien alle 60 Min (clean & minimal)
- **JETZT-Marker**: Roter Badge zeigt aktuelle Zeit prominent
- **Live-Line**: Rote vertikale Linie durch alle Sender
- **Zoom-Funktion**: Skalierbar 50% - 200%
- **Sticky Labels**: Sender-Namen bleiben beim Scrollen sichtbar

#### YouTube Integration (OHNE API Key!)
- **RSS Feeds**: Tagesschau, ZDF heute, Phoenix
- **Chronologische Integration**: YT-Videos nach Veröffentlichungszeit
- **Kombinierte Timeline**: TV + YouTube zusammen sortiert
- **YouTube-Badge**: Rotes YT-Symbol auf Videos

#### Video-Preview Popup
- **Embed-Player**: YouTube-Preview direkt im Popup (ohne Ton)
- **Stylish Overlay**: "VORSCHAU" Badge über Video
- **Titel & Meta**: Channel, Zeit, Beschreibung
- **Action Buttons**: Abspielen, Website-Link

#### Bewertungssystem
- **Stimmungsbarometer**: 👍 Gut, 😐 OK, 👎 Schlecht
- **Live Counter**: Zeigt Anzahl pro Option
- **LocalStorage**: Bewertungen persistent gespeichert
- **Visual Feedback**: Selection highlighting

#### Kommentar-Funktion
- **Textarea**: User können Meinung schreiben
- **Pro Sendung**: Individuelle Kommentare
- **LocalStorage**: Persistent gespeichert
- **Server-Ready**: Vorbereitet für Backend-Integration

#### Zukunfts-Vorschau
- **Ausgegraut**: Future Sendungen mit 40% Opacity
- **Grayscale**: Visual Unterscheidung
- **Nicht klickbar**: pointer-events disabled
- **+8h Preview**: Zeigt kommende Sendungen

#### Filter & Features
- **Kategorien-Filter**: Nachrichten, Talkshows, Kommentar, Dokus, Politik
- **Live-Erkennung**: Rote Border + LIVE Badge
- **Auto-Refresh**: Alle 5 Minuten
- **Responsive**: Mobile-friendly Design

## Technologie

### APIs:
- **MediathekViewWeb API** - Öffentlich-rechtliche Mediatheken
  - ARD, ZDF, Arte, Phoenix, 3sat, BR, WDR, NDR, SWR, HR, MDR, RBB, SR, DW
  - Kostenlos & Open Source
  - Keine API Key benötigt
- **YouTube RSS Feeds** - Kostenlos ohne Quota
  - Tagesschau, ZDF heute, Phoenix
  - Keine API Key benötigt
  - XML Feed Parsing

### Frontend:
- **Pure Vanilla JavaScript** - Keine Frameworks
- **HTML5/CSS3** - Modern & Clean
- **LocalStorage** - Client-side Persistenz
- **Responsive Design** - Mobile & Desktop
- **Dark Theme** - TV-App Aesthetik

## Geplante Features (Roadmap)

### Backend & Infrastruktur
- [ ] **Backend-API** für User-Daten (Node.js/Python)
- [ ] **User-Login System** (OAuth, Email/Password)
- [ ] **Datenbank** für Bewertungen & Kommentare (PostgreSQL/MongoDB)
- [ ] **Real-time Sync** - Bewertungen/Kommentare live synchronisieren

### Community Features
- [ ] **Öffentliche Kommentare** - Alle User-Kommentare anzeigen
- [ ] **User-Profile** - Eigene Timeline mit Bewertungen
- [ ] **Trending Sendungen** - Meist-diskutierte Shows
- [ ] **Notification System** - Alerts für favorisierte Sender/Themen

### Erweiterte Features
- [ ] **Integrated Video Player** - Abspielen direkt in Timeline
- [ ] **Suchfunktion** - Volltext-Suche über alle Sendungen
- [ ] **Favoriten/Watchlist** - Sendungen für später merken
- [ ] **Share-Buttons** - Social Media Integration
- [ ] **Export-Funktion** - Timeline als PDF/iCal
- [ ] **Analytics Dashboard** - Statistiken & Trends visualisieren

### Internationale Erweiterung
- [ ] **ORF** (Österreich) - österreichische Sender
- [ ] **SRF** (Schweiz) - schweizer Sender
- [ ] **Weitere EU-Sender** - Arte FR, BR Alpha International

### Optimierungen
- [ ] **Performance** - Lazy Loading für Sendungen
- [ ] **PWA** - Installierbare App
- [ ] **Offline Mode** - Caching für Timeline
- [ ] **A11y** - Barrierefreiheit verbessern

## Installation

1. Repository klonen
2. `index.html` in Browser öffnen
3. Fertig! Keine Dependencies erforderlich

## Nutzung

### Navigation
- **Scrollen**: Horizontal & Vertikal durch Timeline navigieren
- **Zoom**: +/- Buttons (50% - 200% Skalierung)
- **Kategorien**: Filter für Nachrichten, Talkshows, Kommentar, Dokus, Politik
- **NOW-Marker**: Roter "JETZT" Badge zeigt aktuelle Zeit
- **Live-Line**: Rote vertikale Linie markiert Gegenwart

### Sendungen
- **Live**: Rote Border + LIVE Badge bei laufenden Sendungen
- **Zukunft**: Ausgegraute Sendungen (nicht klickbar)
- **YouTube**: Rotes YT-Symbol auf YouTube-Videos
- **Click**: Öffnet detailliertes Popup

### Popup-Features
- **Video-Preview**: YouTube/Mediathek-Vorschau (ohne Ton)
- **Abspielen**: Direkt zur Mediathek/YouTube
- **Bewerten**: 👍 Gut, 😐 OK, 👎 Schlecht
- **Kommentieren**: Eigene Meinung zur Sendung schreiben
- **Speichern**: Bewertung & Kommentar in LocalStorage

### Pro-Tipps
- Bewertungen & Kommentare bleiben lokal gespeichert
- Zoom rein für mehr Details, raus für Übersicht
- Future-Sendungen zeigen was noch kommt
- YouTube-Videos zeigen neueste Uploads der Sender

## Legal

- Alle Inhalte stammen von öffentlich-rechtlichen Sendern
- Verwendung der MediathekViewWeb API (Open Source)
- Keine Downloads, nur Streaming-Links
- Keine Urheberrechtsverletzungen

## Lizenz

Open Source - für Bildungszwecke und öffentliche Dokumentation

## Kontakt

Projekt: mocracy.de - Democracy through Media Transparency
