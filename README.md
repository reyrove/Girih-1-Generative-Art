# Girih 1 — Generative Art

> A seed-based generative system for Islamic geometric ornament.  
> A reproducible catalogue of computational textile compositions.

---

## What is this?

**Girih 1** is the first volume of a generative design system that translates the classical *girih* tile tradition of Islamic geometry into reproducible algorithmic compositions.

Every artwork in this catalogue is defined by a single numeric seed. The same seed always produces the identical composition — making each piece **traceable, reproducible, and licensable** across textile, print, and surface applications.

This is not a pattern library.  
It is a **system** — one that generates an infinite family of compositions from the same geometric vocabulary.

---

## Live

🌐 **[View the catalogue →](https://reyrove.github.io/Girih-1-Generative-Art/)**

---

## The System

The generator combines two visual languages:

| Layer | Description |
|-------|-------------|
| **Recursive branching** | A tree-like structure drawn with a seeded random generator, forming the fine underlying web. |
| **Geometric motifs** | Three classical-inspired star patterns (`star1`, `star2`, `star3`) derived from girih tile proportions. |

Both layers are driven by the same seed, ensuring deterministic output.

### Motif families

- `Umayyad mosque` — 12-point star tiling
- `Simple hexagram` — 6-point star tiling
- `Esreffoglu mosque` — 6-fold modular star lattice

---

## Structure

```
Girih-1-Generative-Art/
├── index.html          ← Full catalogue (single-file)
├── images/
│   ├── fav.svg
│   ├── tote.png
│   ├── tee.png
│   └── cushion.png
└── README.md
```

The entire project is contained in a single `index.html` — no build step, no dependencies, no framework. Open it in any modern browser.

---

## Features

- **Seed-based generation** — every composition is deterministic and reproducible
- **Live catalogue** — cover, plate, surfaces, process, archive, commission sections
- **Multiple surfaces** — print, scarf, textile, wallpaper — all rendered from the same seed
- **Archive of 8 seeds** — click any plate to load it into the main view
- **PNG export** — download any composition directly from the browser
- **Keyboard shortcuts** — `R` for new seed, `S` to save
- **Legal modal** — licensing, terms, and credits built in
- **Responsive** — works on desktop, tablet, and mobile

---

## Usage

### Generate a new composition

Click **New Seed** or press `R`.

### Download the current composition

Click **Download** or press `S`.

### Load a seed from the archive

Click any plate in the **Archive** section.

---

## Color System

The palette is drawn from three arrays:

- `BackgroundColours1` — deep, saturated tones (used for branching)
- `BackgroundColours2` — soft, paper-like tones (used for leaves)
- `foregroundColours` — cool blue/purple tones (used for geometric motifs)

Each seed selects one color from each array.

---

## Technical Notes

- Pure vanilla JavaScript — no libraries
- Canvas 2D rendering
- Custom xorshift random generator for deterministic seeds
- Device-pixel-ratio aware rendering

---

## About

**Girih 1** is a project by [Reyhaneh Daneshdoost](https://reyrove.github.io/) — an Iranian-born artist working at the intersection of classical Islamic geometry and generative systems.

The work began with a simple observation: the geometric ornament that has decorated mosques, madrasas, and manuscripts for over a thousand years — mathematically rigorous, infinitely repeatable — is almost absent from contemporary digital art.

**Girih 1** is an attempt to close that gap.

> *Ornament, when it is generated rather than drawn, becomes a language — infinite, precise, and quietly yours.*

---

## Licensing

All compositions are seed-documented and available for licensing across textile, surface, and print applications.

For commercial use, custom editions, or exclusive rights:

📧 **reyhanehdaneshdoost@gmail.com**

See the **Licensing** section in the live catalogue for details.

---

## Links

- 🌐 [Website](https://reyrove.github.io/)
- 📷 [Instagram](https://www.instagram.com/rey._.rove/)
- 💼 [LinkedIn](https://www.linkedin.com/in/reyhaneh-daneshdoost-730481160/)
- 🐦 [X](https://x.com/reyrove)

---

## Credits

**Design & Generative System**  
Reyhaneh Daneshdoost

**Typefaces**  
Cormorant Garamond · DM Mono

**Edition**  
Girih 1 — Autumn 2026

---

<p align="center">
  <em>Computational Textile Design</em><br />
  <sub>© Reyrove Studio · All compositions reproducible by seed</sub>
</p>