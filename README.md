# solardome.github.io

Portfolio site for [Denis Miretsky](https://github.com/solardome) — Security Platform Engineer.

Live at **[solardome.github.io](https://solardome.github.io)**.

## What it is

A single-page portfolio that:
- Introduces focus areas: Go, Systems Programming, DevSecOps, Security Platform Engineering, Backend Engineering
- Features hand-curated project cards with in-depth descriptions (`security-gate`, `mini-kvstore`)
- Dynamically loads all public repos from the GitHub REST API

## Stack

Pure HTML / CSS / JavaScript — no build step, no framework. GitHub Pages serves it directly from `main`.

## Updating featured projects

Featured project cards are static HTML inside `index.html`. To add or update one, edit the `<!-- Featured -->` section and follow the existing card structure.

## Local preview

Open `index.html` directly in a browser, or serve it with any static server:

```bash
npx serve .
# or
python3 -m http.server
```
