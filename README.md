# Portfolio Yasmina Yürük

Persönlicher Webauftritt im Rahmen des Kurses **Projekt: Web-Programmierung (DLBUXPWP01)** an der IU Internationale Hochschule.

## Konzept

Die Website ist die erste Version meines Portfolios als Product Owner und Senior Designerin. Sie zeigt meine Projekte, Erfahrungen und meine gestalterische Arbeitsweise und richtet sich an potenzielle Interessent:innen sowie an Menschen, die Inspiration rund um Produktdesign suchen.

Die Gestaltung ist von Tarifa inspiriert. Windsurfen und die Bewegung der Wellen bilden die Grundlage der Gestaltungsidee. Die Wellen ziehen sich als wiederkehrendes visuelles Element durch die Seite.

## Bereiche

- Über mich
- Projekte
- Blog
- Impressum

## Projektstruktur

```
├── index.html          Startseite mit Windsurfer-Navigation
├── ueber-mich.html     Über mich, Werdegang, Profile
├── projekte.html       Projekte (Platzhalter)
├── blog.html           Blogbeiträge
├── impressum.html      Impressum
├── css/
│   └── style.css       Basis-Stylesheet (Farben, Typografie)
├── assets/
│   └── img/            SVG-Grafiken aus dem Figma-Entwurf
└── .github/
    └── workflows/
        └── pages.yml   Veröffentlichung als GitHub Page
```

## Lokale Vorschau

Die Website ist rein statisch. Zur Vorschau `index.html` im Browser öffnen oder in Visual Studio Code die Erweiterung Live Preview nutzen.

## Veröffentlichung

Bei jedem Push auf den Branch `main` veröffentlicht ein GitHub-Actions-Workflow die Website als GitHub Page. Einmalig muss dafür im Repository unter **Settings → Pages → Build and deployment** als Quelle **GitHub Actions** ausgewählt werden.

## Stand: Konzeptionsphase

- Semantisches HTML für alle vier Bereiche plus Startseite
- Barrierefreiheit: `lang="de"`, Sprunglink, `aria-label` und `aria-current` in der Navigation, Alternativtexte, Tabellenbeschriftung
- Basis-Stylesheet mit CSS-Variablen für Farben und Schriften
- Commits nach Conventional Commits
