[README.md](https://github.com/user-attachments/files/25480846/README.md)
# Raumvergabe-App – INVEO / TwoSystem

Eine webbasierte Raumvergabe-Anwendung zur gemeinsamen Buchung von Besprechungsräumen für **INVEO** und **TwoSystem**.

Die App läuft im Browser, ist **online synchronisiert** und kann von überall genutzt werden (Büro, Homeoffice, mobil).

---

## ✨ Funktionen

- 📅 Buchung im **30-Minuten-Takt** von **07:00 – 20:00**
- 🏢 **6 Räume**
  - **1. OG**
    - Raum 1 & 2 → nur **INVEO**
    - Raum 3 & 4 → nur **TwoSystem**
  - **2. OG**
    - Raum 1 & 2 → **beide Unternehmen**
- 🟢 Grün = frei | 🔴 Rot = belegt
- 👤 Login mit **Name, E-Mail & Firma**
- 🔒 Buchungen können **nur vom Ersteller (E-Mail)** gelöscht werden
- 🌍 **Zentrale Synchronisation** für alle Nutzer

---

## 🛠 Technik

- Frontend: HTML, CSS, Vanilla JavaScript
- Backend: Node.js + Express
- Speicherung: In-Memory (Demo / erweiterbar)
- Hosting: GitHub + Cloud-Hosting (z. B. Render)

---

## 📁 Projektstruktur

```
raumvergabe-app
│── server.js
│── package.json
└── public
    └── index.html
```

---

## 🚀 Lokale Installation

### Voraussetzungen
- Node.js (LTS)

### Installation
```
npm install
```

### Starten
```
npm start
```

Danach erreichbar unter:
```
http://localhost:3000
```

---

## 🌐 Online-Betrieb

Die Anwendung ist für den Online-Betrieb vorgesehen und kann über einen zentralen Link
allen Kolleginnen und Kollegen zur Verfügung gestellt werden.

---

## 🔐 Hinweise

- Kein Passwortsystem (bewusst einfach gehalten)
- E-Mail dient zur Identifikation von Buchungen
- Für den Produktivbetrieb wird HTTPS empfohlen

---

## 👤 Verantwortlich

**Johannes Grunert**

---

## 📄 Lizenz

Internes Projekt – Nutzung nach Absprache.
