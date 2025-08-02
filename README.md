# LexSyncTool

LexSyncTool ist eine modulare, erweiterbare Weboberfläche zur automatisierten Verwaltung und Weiterleitung von Dokumenten aus unterschiedlichen Quellen an Lexoffice. Die Anwendung ist als Admin-Dashboard aufgebaut und basiert auf dem TailAdmin-Template (React + Vite + Tailwind CSS).

## 🚀 Features

- **Dashboard:** Zeigt die letzten eingegangenen Dokumente mit Status, Quelle, Datum und Lexoffice-Sendezustand.
- **Plugins:** Übersicht, Konfiguration und Statusanzeige aller Input/Output-Plugins.
- **Lexoffice:** Seite für die Konfiguration und den Status des Lexoffice-Output-Plugins.
- **Status:** Übersicht über Laufzustand, Fehler und Authentifizierungsprobleme aller Plugins.
- **Erweiterbar:** Saubere Trennung der UI-Komponenten, vorbereitet für eigene Plugins und Backend-API.

---

## 📦 Projektstruktur

```
/
├── public/
├── src/
│   ├── components/     # Wiederverwendbare UI-Komponenten
│   ├── data/        # Mock-Daten für Dokumente, Plugins etc.
│   ├── pages/
│   │   ├── Dashboard.jsx
│   │   ├── Plugins.jsx
│   │   ├── Lexoffice.jsx
│   │   └── Status.jsx
│   ├── App.jsx
│   └── main.jsx
├── package.json
├── tailwind.config.js
└── README.md
```

---

## 🛠️ Installation & Start

1. **Repository klonen**

    git clone https://github.com/SpLord/LexSyncTool.git
    cd LexSyncTool

2. **Abhängigkeiten installieren**

    npm install

3. **Entwicklungsserver starten**

    npm run dev

    Das Projekt läuft dann unter http://localhost:5173 (Standard).

---

## ⚙️ Konfiguration

- Die Anwendung arbeitet zunächst mit Mock-Daten (`src/data/`).
- Anbindung an Backend und echte API-Aufrufe kannst du einfach ergänzen, z. B. über Axios oder eigene API-Routen.

---

## 💡 Hinweise

- Das Projekt basiert auf [TailAdmin – Free React Tailwind Admin Dashboard](https://github.com/TailAdmin/free-react-tailwind-admin-dashboard).
- Für eigene Plugins, Authentifizierung oder Logik können einfach weitere Komponenten und Datenquellen eingebunden werden.
- Deployments auf Netlify, Vercel oder als Docker-Container sind problemlos möglich.

---

## 🧑‍💻 Mitmachen

Feature-Wünsche, Bugs oder Pull Requests sind willkommen!

---

## 📄 Lizenz

MIT