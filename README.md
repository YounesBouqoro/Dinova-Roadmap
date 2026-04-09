# Dinova E-Commerce Setup

Operatives GitHub-Setup für den digitalen Vertriebsaufbau von Dinova mit Fokus auf Shopify, Produktdatenstruktur und Marktplatzvorbereitung.

## Ziel des Repositories
Dieses Repository dient als zentrale Steuerungs- und Dokumentationsbasis für das Projekt.

Es bündelt:
- Strategie und Roadmap
- operative Aufgaben und Milestones
- Projektstatus und Risiken
- Entscheidungslogik
- ein einfaches HTML-Dashboard für GitHub Pages

## Empfohlene Nutzung
1. **`docs/strategy.md` lesen** und als strategische Leitplanke nutzen.
2. **GitHub Issues** für jedes Arbeitspaket anlegen.
3. **GitHub Projects** als zentrales Projektboard verwenden.
4. **Dashboard via GitHub Pages** aktivieren, um Status und Roadmap sichtbar zu machen.

## Repository-Struktur
```text
.
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── task.md
│   │   ├── decision.md
│   │   └── risk.md
│   └── workflows/
│       └── pages.yml
├── data/
│   └── dashboard-data.json
├── docs/
│   ├── strategy.md
│   ├── project-board-setup.md
│   ├── issue-plan.md
│   └── github-project-template.md
├── index.html
└── README.md
```

## Empfohlene Labels
- `phase:0-foundation`
- `phase:1-shopify`
- `phase:2-content`
- `phase:3-go-live`
- `phase:4-marketplaces`
- `phase:5-scaling`
- `type:task`
- `type:decision`
- `type:risk`
- `prio:p1`
- `prio:p2`
- `prio:p3`
- `status:blocker`
- `status:waiting-client`

## Vorschlag für GitHub Project Felder
- **Status:** Backlog / Diese Woche / In Arbeit / Waiting for Client / Review / Done
- **Priorität:** P1 / P2 / P3
- **Phase:** 0 / 1 / 2 / 3 / 4 / 5
- **Owner:** zuständige Person
- **Deadline:** Datum
- **Abhängigkeit:** ja/nein

## GitHub Pages aktivieren
1. Repository zu GitHub pushen.
2. In GitHub: **Settings → Pages**.
3. Source: **GitHub Actions** auswählen.
4. Danach wird `index.html` automatisch veröffentlicht.

## Nächste 5 operativen Schritte
1. Labels im Repo anlegen.
2. GitHub Project Board anlegen.
3. Die ersten Issues aus `docs/issue-plan.md` übernehmen.
4. Verantwortlichkeiten und Deadlines setzen.
5. Dashboard-Daten in `data/dashboard-data.json` wöchentlich aktualisieren.
