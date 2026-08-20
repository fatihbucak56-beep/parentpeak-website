<div align="center">
  <h1>parentpeak-website</h1>
  <p>Landing Page für <a href="https://parentpeak.com">parentpeak.com</a></p>

  ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
  ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
  ![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-222?logo=github)
</div>

---

## Überblick

Marketing-Website für [Parentpeak](https://github.com/fatihbucak56-beep/Parentpeak) — die Familien-App für Eltern. Statische Single-Page mit modernem Design, Scroll-Animationen und responsive Layout.

**Live:** [parentpeak.com](https://parentpeak.com)

## Tech Stack

| Technologie | Einsatz |
|-------------|---------|
| HTML5 | Semantisches Markup, SEO-Meta-Tags, Open Graph |
| CSS3 | Custom Properties, Grid, Flexbox, Animations |
| JavaScript | Intersection Observer, Smooth Scroll, Mobile Menu |
| Google Fonts | Inter (400–900) |
| GitHub Pages | Hosting via Custom Domain |

## Features

- Responsive Design (Mobile-first Breakpoints: 640px, 900px)
- Scroll-triggered Animations via Intersection Observer
- SEO-optimiert (Meta Tags, Open Graph, Twitter Cards, Canonical URL, Sitemap)
- Accessibility: Semantic HTML, ARIA Labels, Focus States
- Performance: Minimal JS, keine Frameworks, Preconnect für Fonts
- Mobile Menu mit Hamburger Toggle
- Pricing Section mit 3 Tiers (Free / Premium / Anbieter)

## Projektstruktur

```
├── index.html          # Hauptseite
├── style.css           # Alle Styles (CSS Custom Properties)
├── script.js           # Interaktionen (Scroll, Menu, Nav)
├── assets/             # Bilder, Icons
├── robots.txt          # Crawler-Konfiguration
├── sitemap.xml         # XML-Sitemap für SEO
├── check-site.mjs      # Link-Check Script
├── CNAME               # Custom Domain Config
└── .github/workflows/  # Deploy Pipeline
```

## Lokal starten

```bash
# Einfach öffnen — kein Build-Schritt nötig
open index.html

# Oder mit Live-Server (VS Code Extension)
# Oder Python:
python3 -m http.server 8000
```

## Deployment

Automatisch via GitHub Pages bei Push auf `main`.

Custom Domain: `parentpeak.com` (CNAME konfiguriert)

## Lighthouse Ziele

| Kategorie | Ziel |
|-----------|------|
| Performance | > 90 |
| Accessibility | > 95 |
| Best Practices | > 95 |
| SEO | > 95 |

## Zusammengehörige Repos

| Repo | Beschreibung |
|------|-------------|
| [Parentpeak](https://github.com/fatihbucak56-beep/Parentpeak) | Flutter App (Haupt-Repository) |
| [parentpeak-website](https://github.com/fatihbucak56-beep/parentpeak-website) | Dieses Repo — Landing Page |

---

<div align="center">
  <sub>© 2026 Fatih Bucak — Parentpeak. Alle Rechte vorbehalten.</sub>
</div>
