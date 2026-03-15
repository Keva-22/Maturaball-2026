# Carpe Noctem — Maturaball 2026
### Herzjesu Gymnasium Innsbruck

> *"Carpe Noctem — 8 Jahre, eine Nacht"*

Offizielle Website des Maturaballs 2026.

---

## 📁 Projektstruktur

```
carpe-noctem-ball/
├── index.html              # Startseite (Hero, Programm, Location, Tickets-CTA)
├── css/
│   ├── style.css           # Globale Styles (Navigation, Farben, Typografie)
│   ├── index.css           # Styles für die Startseite
│   └── inner-page.css      # Styles für alle Unterseiten
├── js/
│   └── main.js             # Navigation, Countdown, Sternenhimmel, Animationen
└── pages/
    ├── komitee.html         # Das Ballkomitee
    ├── tickets.html         # Ticketkauf & FAQ
    └── impressum.html       # Impressum & Datenschutz
```

---

## 🎨 Design

- **Thema:** Luxuriöse Mitternacht · Art Déco · Celestial
- **Farben:** Tiefdunkles Midnight Navy (#06060f) · Gold (#c9962c) · Champagne (#f5edd6)
- **Schriften:** Cinzel Decorative (Headings) · EB Garamond (Fließtext)
- **Features:** Animierter Sternenhimmel, Live-Countdown, Scroll-Animationen, Responsive Design

---

## 🚀 Deployment

### Lokale Vorschau
Einfach `index.html` im Browser öffnen — kein Build-Schritt nötig!

### GitHub Pages
1. Repo auf GitHub erstellen
2. Alle Dateien pushen
3. In den Repo-Einstellungen unter *Pages* → Source: `main` Branch, Root `/`
4. Die Seite ist unter `https://[username].github.io/[repo-name]` erreichbar

### Eigene Domain
1. DNS: CNAME-Eintrag auf `[username].github.io` setzen
2. In GitHub Pages die Custom Domain eintragen

---

## ✏️ Anpassen

| Was | Wo |
|---|---|
| Schule / Namen anpassen | Alle HTML-Dateien |
| Ticket-Preise | `pages/tickets.html` |
| Programm-Uhrzeiten | `index.html`, Abschnitt `#programm` |
| Komitee-Mitglieder | `pages/komitee.html` |
| Location-Details | `index.html`, Abschnitt `#location` |
| Balltermin im Countdown | `js/main.js`, Zeile mit `new Date('2026-11-21T20:00:00')` |
| Kontakt-E-Mail | `pages/komitee.html`, `pages/impressum.html` |

---

## 🛠️ Technologien

- Reines HTML5, CSS3, Vanilla JS — **kein Framework, kein Build-Tool**
- Google Fonts: [Cinzel Decorative](https://fonts.google.com/specimen/Cinzel+Decorative) + [EB Garamond](https://fonts.google.com/specimen/EB+Garamond)
- Canvas API für den Sternenhimmel
- IntersectionObserver für Scroll-Animationen

---

*Made with ♡ by the Ballkomitee Herzjesu 2026*
