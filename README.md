# Schichtplaner

Ein schlanker, webbasierter Schichtplaner für kleine Betriebe — läuft lokal auf deinem Rechner, keine Cloud, keine Abhängigkeiten.

---

## Wozu dient der Schichtplaner?

Der Schichtplaner hilft dir dabei, die Arbeitszeiten deiner Mitarbeiter zu planen, Urlaub zu verwalten und am Ende des Monats auszuwerten, wer wie viele Stunden gearbeitet hat. Alles läuft lokal — deine Daten bleiben auf deinem Rechner.

---

## Features

### Planungskalender
Trage Arbeitstage und Urlaubstage pro Mitarbeiter per Klick ein. Der Kalender zeigt dir auf einen Blick, wer wann arbeitet.

### Dashboard
Die Startseite gibt dir eine sofortige Monatsübersicht: Wer hat sein Soll erfüllt? Wer hat noch Resturlaub? Wie viele Mitarbeiter sind aktiv?

### Monatsauswertung
Pro Mitarbeiter oder für alle auf einmal — als PDF oder CSV exportierbar. Ideal für die Lohnabrechnung oder das Gespräch mit dem Steuerberater.

### Urlaubsverwaltung
Jeder Mitarbeiter hat ein konfigurierbares Urlaubskontingent. Der Schichtplaner zeigt dir jederzeit, wie viel Resturlaub noch vorhanden ist.

### Feiertage
Bundesweite und bundeslandspezifische Feiertage werden automatisch berücksichtigt. Für Betriebe, die an Feiertagen arbeiten (z. B. Kinos), gibt es einen eigenen Modus.

### Schichtplan-Validierung
Der Schichtplaner warnt dich, wenn du etwas Ungültiges planst — z. B. einen Arbeitstag auf einem Urlaubstag oder ein erschöpftes Urlaubskontingent. Die Hinweise erscheinen als dezente Toast-Meldungen, ohne den Workflow zu unterbrechen.

### Notizen
Auf einzelnen Arbeitstagen können kurze Notizen hinterlegt werden — z. B. für besondere Aufgaben oder Absprachen.

### CSV-Import
Arbeitstage lassen sich aus externen Systemen per CSV importieren. Duplikate werden automatisch übersprungen.

### Mitarbeiter archivieren
Ausgeschiedene Mitarbeiter werden nicht gelöscht, sondern archiviert — so bleibt die Historie erhalten.

### Setup-Wizard
Beim ersten Start führt ein kurzer Assistent durch die Erstkonfiguration. Kein manuelles Einrichten notwendig.

### Hell- und Dunkel-Modus
Die Oberfläche folgt automatisch der Systemeinstellung — natürlich auch manuell umschaltbar.

### Automatisches Backup
Bei jedem App-Start wird automatisch ein Backup der Datenbank angelegt.

---

## Installation

1. Die passende Datei für dein Betriebssystem unten herunterladen und entpacken
2. Ausführen:

**Windows:**
```
Schichtplaner.exe
```

**Linux:**
```bash
chmod +x ./SchichtplanerWebApp
./SchichtplanerWebApp
```

3. Der Browser öffnet sich automatisch
4. Beim ersten Start führt ein Setup-Wizard durch die Erstkonfiguration
5. Einloggen mit `admin` / `admin` — **Passwort danach bitte sofort ändern**

> Keine Installation, keine Cloud, keine Abhängigkeiten. Die App bringt alles mit, was sie braucht.

---

## Bekannte Einschränkungen

- Aktuell nur ein Benutzer-Account (`admin`) — Mehrbenutzerverwaltung ist geplant
- Krankmeldungen werden nicht separat erfasst, nur Urlaub und Arbeitstage
- Ein Mitarbeiter hat genau eine feste Schicht — flexible Schichtzuweisung pro Tag ist noch nicht möglich

