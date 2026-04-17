# 🎲 Wie oft würfelst du welche Augenzahl?

Dieses Projekt ermöglicht es Schülerinnen und Schülern, ihre Würfelergebnisse digital einzugeben und gemeinsam auszuwerten. Die Daten werden in einer Firebase-Datenbank gespeichert und im Dashboard visualisiert.

---

## 📁 Projektstruktur

- index.html → Eingabeseite für die Schülerinnen und Schüler  
- dashboard.html → Anzeige der Ergebnisse (Tabelle + Säulendiagramm)  
- firebase-config.js → Verbindung zur Firebase-Datenbank  

---

## 🚀 Funktionen

### Eingabeseite (index.html)
- Eingabe der Gruppennummer und Würfelergebnisse (1–6)
- Automatische Berechnung der Gesamtwürfe
- Eingabefelder:
  - „0“ verschwindet automatisch beim Tippen
  - leere Felder werden wieder zu „0“
- Daten werden per Klick auf „senden“ gespeichert

---

### Dashboard (dashboard.html)
- Anzeige aller Gruppen-Ergebnisse in einer Tabelle
- Automatische Sortierung nach Gruppennummer
- Visualisierung als Säulendiagramm
- Anzeige von:
  - Anzahl der Gruppen
  - Gesamtanzahl der Würfe

---

## 🔧 Einrichtung

1. Firebase-Projekt erstellen  
2. Firebase-Konfiguration in firebase-config.js eintragen  
3. Dateien auf Webserver oder Firebase Hosting hochladen  

---

## 🔑 Nutzung

### Für Schülerinnen und Schüler:
1. Eingabeseite öffnen (index.html)
2. Passwort eingeben (z. B. „44“)
3. Gruppennummer eintragen
4. Würfelergebnisse eingeben
5. Auf „senden“ klicken

---

### Für die Lehrkraft:
1. Dashboard öffnen (dashboard.html)
2. Passwort eingeben
3. Auf „anzeigen“ klicken
4. Ergebnisse gemeinsam auswerten

---

## 📊 Didaktischer Einsatz

- Förderung des Verständnisses von Zufall und Wahrscheinlichkeit
- Gemeinsame Datenerhebung im Klassenverband
- Visualisierung von Häufigkeiten

---

## 👩‍🏫 Autorin

Leonie Auer  
Lehramtsanwärterin (Primarstufe)  
Fach: Mathematik  
