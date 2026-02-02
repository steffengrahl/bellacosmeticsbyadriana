<img src="images/hero-logo-banner.png" alt="Bella Cosmetics Hero Banner" width="600">

# Bella Cosmetics by Adrianna

[![Pages Deployment](https://img.shields.io/github/deployments/steffengrahl/bellacosmeticsbyadriana/github-pages?label=deployment)](https://github.com/steffengrahl/bellacosmeticsbyadriana/deployments)
[![Lizenz](https://img.shields.io/github/license/steffengrahl/bellacosmeticsbyadriana?color=blue)](LICENSE)
[![Website Status](https://img.shields.io/website?url=https%3A%2F%2Fadrianna.steffengrahl.de&label=website)](https://www.bellacosmeticsbyadrianna.de)

Willkommen im offiziellen Repository der Website von **Bella Cosmetics by Adrianna**, einem exklusiven Kosmetikstudio in Berlin-Neukölln. Diese Website dient als digitale Visitenkarte und Informationsplattform für Dienstleistungen wie Permanent Make-up, professionelle Fußpflege, Wimpern-Design und Plasma-Pen-Behandlungen.

Die Seite wurde als performante, statische Webpräsenz konzipiert, die modernen Standards in Bezug auf Ladegeschwindigkeit (LCP), Barrierefreiheit und Datenschutz entspricht.

## Live-Umgebungen

- **Produktion:** [https://www.bellacosmeticsbyadrianna.de](https://www.bellacosmeticsbyadrianna.de)
- **Staging:** [https://adrianna.steffengrahl.de](https://adrianna.steffengrahl.de)

## Tech Stack & Optimierungen

- **Frontend:** Pures HTML5 und CSS3 (Custom Styles).
- **Hosting:** GitHub Pages für maximale Verfügbarkeit und Kosteneffizienz.
- **Performance:** Optimierte `.webp`-Bilder und Nutzung von `fetchpriority="high"` für kritische Ressourcen (LCP).
- **Accessibility:** Semantisches HTML, Skip-to-Content Links und Fokus-Management für Tastaturbenutzer.
- **Formulare:** Integration von **forminit** für datenschutzkonforme Kontaktanfragen.

## Projektstruktur & Dokumentation

Weitere technische Details und rechtliche Einordnungen finden sich im Ordner `docs/`:

- [**Styleguide**](docs/styleguide.md): Dokumentation von Farben, Typografie und UI-Komponenten.
- [**GitHub Pages Vertretbarkeit**](docs/github-pages-vertretbarkeit.md): Datenschutzrechtliche Einordnung des Hostings.

## Lokale Entwicklung

Da es sich um eine statische Website handelt, kann sie direkt im Browser geöffnet oder über einen lokalen Webserver bereitgestellt werden.

### Einfacher Webserver (Python)

Wenn Python installiert ist, kann ein Server im Stammverzeichnis gestartet werden:

```bash
python3 -m http.server 8080
```

Die Seite ist dann unter `http://localhost:8080` erreichbar.

### Docker (GitHub Pages Simulation)

Um die Umgebung von GitHub Pages lokal mittels Docker (Nginx) nachzustellen, kann folgender Befehl verwendet werden:

```bash
docker run --name bella-cosmetics --rm -p 8080:80 -v $(pwd):/usr/share/nginx/html:ro -d nginx:alpine
```

Die Website ist anschließend unter `http://localhost:8080` erreichbar. Um den Container zu stoppen (er wird durch `--rm` automatisch entfernt):

```bash
docker stop bella-cosmetics
```

## Autoren

- **Adrianna Bryn** ([Bella Cosmetics](https://www.bellacosmeticsbyadrianna.de)) – Inhaberin und Betreiberin.
- **Steffen Grahl** ([SGWebservice](https://sgwebservice.de)) – Verantwortlicher Entwickler.

## Lizenz

Der Quellcode dieser Website unterliegt der MIT-Lizenz. Details finden sich in der [LICENSE.md](LICENSE.md).

## Mitwirken

Aktuell ist keine externe Mitarbeit am Projekt vorgesehen.
