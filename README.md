# 🎲 Würfel-Statistik – Unterrichtsprojekt

Dieses Projekt ist eine einfache Webanwendung für den Mathematikunterricht (Grundschule), mit der Schülerinnen und Schüler ihre Würfelergebnisse eingeben und gemeinsam auswerten können.

## 🚀 Funktionen

- Eingabe von Würfelergebnissen (Augenzahl 1–6) pro Gruppe  
- Automatische Berechnung der Gesamtanzahl der Würfe  
- Speicherung der Daten in einer Firebase Realtime Database  
- Anzeige aller Ergebnisse im Dashboard:
  - 📊 Säulendiagramm
  - 📋 Tabelle mit allen Gruppen
  - 🔢 Gesamtanzahl der Gruppen und Würfe  

---

## 🧩 Projektstruktur

- index.html → Eingabeseite für Schülerinnen und Schüler  
- dashboard.html → Auswertungsseite für die Lehrkraft  
- firebase-config.js → Verbindung zur Firebase-Datenbank  

---

## ⚙️ Einrichtung

### 1. Firebase Projekt erstellen

1. Gehe zur Firebase Console  
2. Neues Projekt erstellen  
3. Realtime Database aktivieren  
4. Web-App hinzufügen  

### 2. Firebase konfigurieren

Trage deine eigenen Firebase-Daten in die Datei firebase-config.js ein:

```js
const firebaseConfig = {
  apiKey: "...",
  authDomain: "...",
  databaseURL: "...",
  projectId: "...",
};
```

---

## ▶️ Nutzung

### Für Schüler:innen

1. Öffne index.html
2. Gib ein:
   - Passwort (z. B. Unterrichtscode)
   - Gruppennummer
3. Trage die Würfelergebnisse ein
4. Klicke auf „senden“

---

### Für die Lehrkraft

1. Öffne dashboard.html
2. Gib das gleiche Passwort ein
3. Klicke auf „anzeigen“
4. Ergebnisse werden live dargestellt

---

## 🔗 Datenstruktur (Firebase)

```
Stunde4/
  [lessonCode]/
    groups/
      [groupName]/
        counts:
          1: Zahl
          ...
        total: Zahl
```

---

## 💡 Einsatz im Unterricht

Dieses Tool eignet sich besonders für Themen wie:

- Zufallsexperimente  
- Häufigkeiten  
- Wahrscheinlichkeit  
- Daten auswerten  

---

## 🛠️ Technologien

- HTML, CSS, JavaScript  
- Firebase Realtime Database  

---

## 📌 Hinweise

- Keine Anmeldung notwendig  
- Funktioniert direkt im Browser  
- Ideal für Tablets oder Computer im Klassenzimmer  

---

## ✏️ Autorin

Leonie Auer  

---

## 📄 Lizenz

Dieses Projekt kann frei für Unterrichtszwecke verwendet werden.
