# 🎲 Würfel-Statistik Dashboard

Diese Web-App zeigt die Ergebnisse von Würfelexperimenten
übersichtlich und in Echtzeit an.

## 🚀 Funktionen

- Anzeige aller Gruppenergebnisse
- Automatische Summenberechnung
- Balkendiagramm zur Visualisierung
- Live-Updates aus Firebase
- Sortierung der Gruppen nach Nummer

## 📁 Projektstruktur

- `dashboard.html` → Auswertung & Visualisierung
- `firebase-config.js` → Firebase-Verbindung

## ⚙️ Einrichtung

1. Firebase-Projekt erstellen
2. Realtime Database aktivieren
3. Firebase-Konfigurationsdaten in `firebase-config.js` eintragen
4. Dateien auf Webserver oder Firebase Hosting hochladen

## 🧠 Hinweise

- Daten werden aus folgendem Pfad geladen:
  `Stunde4/{Passwort}/groups`
- Es werden alle Augenzahlen (1–6) automatisch aufsummiert
- Diagramm passt sich dynamisch an die Werte an

## 📊 Nutzung im Unterricht

Ideal für:
- Wahrscheinlichkeit (Klasse 4)
- Würfelexperimente
- Häufigkeiten vergleichen
- Gesetz der großen Zahlen vorbereiten

## 👩‍🏫 Autorin

Leonie Auer
