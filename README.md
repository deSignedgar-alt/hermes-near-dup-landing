# Hermes Fleur — technical landing

Static site for GitHub Pages. Audience: CISO / risk / IT / СБ (anti-marketing).

| Path | Role |
|------|------|
| `index.html` | Product page — SKU `hermes-l2-suite` (Base / Rotate / Angle) |
| `trust.html` | IT/CISO trust layer (air-gap, no telemetry, volumes, soft-lock) |
| `poc-agreement.html` | Lightweight 1000-match / 14-day PoC terms (Print → PDF) |
| `assets/favicon.svg` | Mark |

**Contact:** Igor Haritonof · `dezignedgar@gmail.com` (set in `index.html`).

## Claims aligned to suite freeze

- Cascade Base → D₄ → Angle, **1 tick** / match  
- Lab N=8: jpeg / rot90 / ±15° Pro floors; hard-alien FPR 0/48  
- Pilot: Docker pack, local audit opt-in, **no phone-home**  
- Not sold: beyond ±15°, perspective/warp fraud oracle, auto-deny  

## Local preview

```powershell
cd landing
python -m http.server 5500
# http://127.0.0.1:5500
```

## GitHub Pages

Workflow: [`.github/workflows/deploy-landing.yml`](../.github/workflows/deploy-landing.yml) uploads this folder to Pages on push to `main` (or manual `workflow_dispatch`).

Pitch language matches product passport: near-dup / suite cascade / advisory — not a fraud oracle.
