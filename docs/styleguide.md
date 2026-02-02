# Styleguide - Bella Cosmetics by Adrianna

Dieser Styleguide dokumentiert die visuellen und technischen Design-Vorgaben für die Website von Bella Cosmetics by Adrianna. Er dient als Referenz für zukünftige Erweiterungen, um ein konsistentes Erscheinungsbild zu gewährleisten.

## 1. Farbpalette

Die Farben sind erdig, elegant und beruhigend gewählt, um die Atmosphäre des Kosmetikstudios widerzuspiegeln.

| Farbe | HEX-Code | Verwendung |
| :--- | :--- | :--- |
| **Shade 1** | `#dbc6b6` | Navigation-Hintergrund, Header-Hintergrund, Kontakt-Sektion |
| **Shade 2** | `#6e594a` | Footer-Hintergrund, Primär-Buttons, Skip-Link |
| **Main Color** | `#c08a7a` | Akzentfarbe, Hover-Status für Buttons |
| **Secondary** | `#c6b4ac` | Trennlinien (z.B. Preislisten) |
| **Ink** | `#3b2a22` | Haupt-Textfarbe (Dunkelbraun) |
| **White** | `#ffffff` | Hintergrund für Hauptinhalte, Text in dunklen Sektionen |
| **Accent Rose**| `#e05a7a` | Optionale Akzentfarbe |

---

## 2. Typografie

Die Typografie nutzt Google Fonts (lokal gehostet), die eine Mischung aus moderner Eleganz und guter Lesbarkeit bieten.

- **Überschriften (H1, H2):** `Julius Sans One`, serif.
  - *Charakter:* Filigran, weit laufend, elegant.
  - *Einsatz:* Hauptüberschriften der Sektionen.
- **Unterüberschriften (H3-H6) & Body:** `Archivo Narrow`, sans-serif.
  - *Charakter:* Funktional, kompakt, modern.
  - *Einsatz:* Fließtext, Listen, Navigation, Buttons.

**Schriftgrößen (Basis):**
- Body: `18px`
- H1: `2.6rem` (Detailseiten) / `2.4rem` (Legal)
- H2: `1.4rem` bis `1.8rem`

---

## 3. Layout & Komponenten

### Container
- **Standard-Max-Breite:** `1260px`
- **Legal-Seiten Max-Breite:** `960px` (für bessere Lesbarkeit von Texten)
- **Padding:** Seitlich `1rem`.

### Navigation
- **Header:** Hintergrund `Shade 1`. Links in Uppercase mit 2px Unterstreichung bei Hover/Aktiv.
- **CTA-Button:** Hintergrund `Shade 2`, abgerundet (`8px`).

### Buttons & Interaktion
- **Primär-Button:** Hintergrund `Shade 2`, Text weiß, abgerundet (`6px` oder `8px`).
- **Hover-Effekt:** Übergang zu `Main Color` oder leichte Aufhellung.
- **Fokus-Status:** Deutliche Markierung für Tastaturnutzer (Skip-Link wird sichtbar).

### Karten (Service Cards)
- Weißer Hintergrund mit dezentem Schatten oder Rahmen (je nach Kontext).
- Bild oben oder links (Grid-Layout).
- Abgerundete Ecken (`10px` für Bilder).

---

## 4. Bildsprache
- **Stil:** Hell, freundlich, professionell.
- **Format:** Bevorzugt modernste Formate wie `.webp` für Performance.
- **Icons:** SVG-Icons in `Ink` oder `White`, minimalistisch.

---

## 5. Technische Prinzipien
- **Mobile First:** Die Seite ist responsiv optimiert (Breakpoints bei `900px`, `640px` etc.).
- **Performance:** Wichtige Bilder (Logos, LCP-Elemente) nutzen `fetchpriority="high"`.
- **Barrierefreiheit:** 
  - Verwendung semantischer HTML-Tags (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`).
  - Vorhandensein eines "Skip to Content"-Links.
  - Ausreichende Kontraste zwischen Text und Hintergrund.

---
*Stand: Februar 2026*
