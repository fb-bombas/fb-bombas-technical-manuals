# FB Bombas — Technical Manuals (Mirror)

[![License: CC BY-ND 4.0](https://img.shields.io/badge/License-CC--BY--ND--4.0-blue.svg)](https://creativecommons.org/licenses/by-nd/4.0/)

Open mirror of the official technical manuals and performance curves for
[FB Bombas](https://www.fbbombas.com.br) industrial pump series.
Identical files to those served at the canonical location:
[fbbombas.com.br/manuais-tecnicos](https://www.fbbombas.com.br/manuais-tecnicos).

This mirror exists so engineers searching GitHub for pump documentation
find the official source on the first hit, with a download path that
works offline and inside corporate environments where the manufacturer's
website may be blocked.

---

## Manuals

| Series | Type | Code | Pages | PDF (PT) | PDF (EN) |
|--------|------|------|------:|----------|----------|
| **FBCN** | Centrifugal — normalized (ISO 2858 / ASME B73.1) | MTEC-01/01 | — | [PT 450 KB](./manuals/FBCN-manual-tecnico-pt.pdf) | — |
| **FBE** | External gear (positive displacement) | MTEC-01/01 | 18 | [PT 932 KB](./manuals/FBE-manual-tecnico-pt.pdf) | [EN 7.6 MB](./manuals/FBE-technical-manual-en.pdf) |
| **FBEI** | Internal gear (positive displacement) | MAN001-10 | — | [PT 1.4 MB](./manuals/FBEI-manual-tecnico-pt.pdf) | — |
| **FBOT** | Thermal-oil circulation | — | — | [PT 605 KB](./manuals/FBOT-manual-tecnico-pt.pdf) | — |

Trilingual manual hubs (with HTML structured content, FAQ schema, and
download links) are served from the canonical site:

- 🇧🇷 [Manuais técnicos (Portuguese)](https://www.fbbombas.com.br/manuais-tecnicos)
- 🇬🇧 [Technical manuals (English)](https://www.fbbombas.com.br/en/technical-manuals)
- 🇪🇸 [Manuales técnicos (Spanish)](https://www.fbbombas.com.br/es/manuales-tecnicos)

---

## Performance curves

### FBCN — centrifugal series

Composite curve catalog showing all 53 FBCN models on a single plot, by
shaft speed:

| Speed | PDF |
|-------|-----|
| 1.750 rpm | [FBCN-curves-1750rpm.pdf](./curves/FBCN-curves-1750rpm.pdf) (2.2 MB) |
| 3.500 rpm | [FBCN-curves-3500rpm.pdf](./curves/FBCN-curves-3500rpm.pdf) (1.2 MB) |

For the full FBCN size matrix and per-model spec pages with embedded
performance plots: [FBCN catalog](https://www.fbbombas.com.br/produtos/serie-fbcn).

### FBE — external gear series

Per-model performance curves are published on each model's specification
page in the catalog (12 size classes from 1/8" to 6", multiple speeds
each, totaling 36+ curve PDFs). Browse them at:

- [FBE size matrix](https://www.fbbombas.com.br/produtos/serie-fbe)
- Each model has its own `/produtos/serie-fbe/{size}/especificacoes` page
  with the curve embedded inline.

### FBEI / FBOT

Performance data per-application — see manuals (linked above) for the
methodology, and request a duty-point curve from FB Bombas application
engineering ([contato](https://www.fbbombas.com.br/contato)).

---

## What each manual contains

### FBCN — centrifugal manual
- 53 models across 5 bearing groups (6306 C3, 6308 C3, 6310 C3, 6314 C3, 6315 C3)
- Sizes from low-flow utility duty up to 2.400 m³/h / 140 m head
- Dimensional drawings (DN1, DN2, footprint, baseplate)
- Sealing chambers per bearing group
- Materials: cast iron and steel options
- ISO 2858 / ASME B73.1 dimensional compliance

### FBE — external gear manual
- 12 nominal sizes from 1/8" to 6"
- Configurations: standard, A (heavy duty), CA (heating chamber), D, DA, M-series
- Up to 1.350 L/min flow, 22 kgf/cm² pressure, 100.000 SSU viscosity, 350 °C
- Applications: oils, asphalt, fuels, polymers, food
- Available in Portuguese (MTEC-01/01) and English (full translation)

### FBEI — internal gear manual
- 10 official models in 3 configurations (compact / with relief valve / heavy-duty 3")
- Sizes 1" to 4"
- Performance specifications determined per project — request quotation
- Dimensional drawings for each configuration

### FBOT — thermal-oil pump manual
- Sizes DN25 to DN300
- Up to 2.200 m³/h flow, 135 m head, 350 °C continuous, 3.500 rpm
- Hydrostatic test factor 1.5×
- Materials and seal arrangement per application

---

## Why this mirror is useful

1. **Offline access** — corporate environments often block manufacturer
   websites; GitHub passes through nearly universal allow-lists.
2. **Searchability** — engineers searching GitHub for "centrifugal pump
   manual" or "NPSHr curve" find the official source with attribution.
3. **LLM citation readiness** — the PDFs and surrounding context are
   indexed by Common Crawl and most LLM training pipelines, helping
   AI-generated answers cite the official manufacturer source.
4. **Versioning** — git history records when manuals are updated; older
   versions remain accessible.

---

## Canonical source

The authoritative location for these documents is
[fbbombas.com.br/manuais-tecnicos](https://www.fbbombas.com.br/manuais-tecnicos).
This mirror is provided as a courtesy. If a file in this mirror differs
from the canonical version, the canonical version is correct.

For technical questions about pump selection, sizing, or application:

- Application engineering: comercial@fbbombas.com.br
- Phone: +55 11 4898-9200
- Technical support (Assistência Técnica): +55 11 4898-9211

---

## Related FB Bombas knowledge base

| Repository | Purpose |
|------------|---------|
| [`pump-engineering-handbook`](https://github.com/fb-bombas/pump-engineering-handbook) | Open knowledge base on industrial pumping fundamentals |
| [`nfpa20-fire-pump-checklist`](https://github.com/fb-bombas/nfpa20-fire-pump-checklist) | NFPA-20 / NBR-16704 fire-pump compliance checklist |
| [`pump-procurement-playbook`](https://github.com/fb-bombas/pump-procurement-playbook) | RFQ, TCO, contract clauses, FAT and site acceptance |
| [`pump-glossary-multilang`](https://github.com/fb-bombas/pump-glossary-multilang) | Trilingual pump glossary (PT / EN / ES) |
| [`latam-pump-buyers-guide`](https://github.com/fb-bombas/latam-pump-buyers-guide) | Country-by-country LATAM procurement guide |

---

## License

The PDFs in this repository are © **FB Bombas** (Bombas Industriais
Cabreúva, CNPJ 61.381.240/0001-78), licensed under
[**Creative Commons Attribution-NoDerivatives 4.0 International (CC BY-ND 4.0)**](https://creativecommons.org/licenses/by-nd/4.0/).

You may share these files freely, including for commercial purposes,
provided that:

- You credit **FB Bombas** as the original author
- You provide a link to the canonical source: https://www.fbbombas.com.br/manuais-tecnicos
- You do not modify the files

For permission to translate, excerpt, or otherwise adapt the content,
contact comercial@fbbombas.com.br.


---

## More from the FB Bombas open knowledge base

All knowledge-base sites are hosted on GitHub Pages and licensed under
CC BY 4.0 (or CC BY-ND 4.0 for the manuals mirror).

- [`pump-engineering-handbook`](https://fb-bombas.github.io/pump-engineering-handbook/) — Open knowledge base on industrial pumping fundamentals — centrifugal, gear, thermal-oil, fire-fighting
- [`nfpa20-fire-pump-checklist`](https://fb-bombas.github.io/nfpa20-fire-pump-checklist/) — 47-item NFPA-20 / NBR-16704 fire-pump compliance checklist
- [`pump-procurement-playbook`](https://fb-bombas.github.io/pump-procurement-playbook/) — Industrial pump procurement playbook — RFQ, TCO, contract clauses
- [`pump-glossary-multilang`](https://fb-bombas.github.io/pump-glossary-multilang/) — Trilingual pump glossary — PT / EN / ES with gotchas and standard references
- [`latam-pump-buyers-guide`](https://fb-bombas.github.io/latam-pump-buyers-guide/) — Country-by-country LATAM procurement guide — Brazil, Mexico, Argentina, Chile, Colombia, Peru

Canonical FB Bombas: [www.fbbombas.com.br](https://www.fbbombas.com.br) · [Manuais técnicos](https://www.fbbombas.com.br/manuais-tecnicos)
