# Christina Martini Yoga — concept redesign

Pitch redesign of **christinamartiniyoga.com** (Shala Santosha, Haiku-Pauwela, Maui)
for Frontline Web Designs. Christina Martini is a senior authorized Ashtanga lineage
teacher *and* a 30-year oncology / chronic-care nurse.

## Status
- **PITCH CONCEPT — not deployed, not Christina's signed-off site.**
- Every page carries `noindex, nofollow`.
- No git remote / Netlify / Hostinger wired yet (intentional).

## Stack
Single shared `styles.css` + `main.js`, six static HTML pages. No frameworks, no build step.

| File | Page |
|---|---|
| `index.html` | Home — hero "Practice in safe hands" |
| `about.html` | Christina's story & credentials |
| `practice.html` | Classes (Mysore/led) + 1:1 therapy + schedule + rates |
| `training.html` | RYT-200, 6-day therapy immersion, 7-day retreat |
| `oncology.html` | Oncology & chronic-care yoga therapy + nurse advocacy |
| `contact.html` | Visit / contact / map |

## Design declarations
- **Type:** Newsreader (display serif) × IBM Plex Sans (body) + IBM Plex Mono (clinical chart labels).
- **Color:** `--bg #F4F1EA` · `--surface #EAE4D7` · `--ink #23291F` · `--primary #2F4A3E` · `--accent #A4492A`. All text ≥ 4.5:1 (WCAG AA).
- **Hero:** asymmetric editorial split, claim "Practice in *safe hands.*"
- **Motif:** "the breath line" — a clinical baseline that rises into one calm arc.
- **One word:** SAFE.

## Confirm with Christina before any live deploy
- [ ] Real photography (every `.frame` block has a dimensioned HTML comment spec).
- [ ] Class **schedule** days/times (placeholders on `practice.html`).
- [ ] **Rates & tuition** (placeholders marked with a dashed "confirm" ribbon).
- [ ] Hours on `contact.html`.
- [ ] Contact details (pulled from her current site — verify still current).
- [ ] Wire the contact form to a real backend (Formspree / Netlify Forms / email).
- [ ] Add a real map embed on `contact.html`.
- [ ] Add testimonials (intentionally omitted — no fabricated reviews).
- [ ] Remove `noindex` once approved.
