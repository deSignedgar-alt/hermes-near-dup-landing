# Hermes Fleur — technical landing

Static site for GitHub Pages. Audience: CISO / risk / IT / СБ (anti-marketing).

| Path | Role |
|------|------|
| `index.html` | Product page — SKU `hermes-l2-suite` (Base / Rotate / Angle) |
| `trust.html` | IT/CISO trust layer (air-gap, no telemetry, volumes, soft-lock) |
| `poc-agreement.html` | Lightweight 1000-match / 14-day PoC terms (Print → PDF) |
| `assets/favicon.svg` | Mark (SVG) |
| `favicon.ico` | Root ICO for browser tabs / crawlers |
| `robots.txt` | `User-agent: *` / `Allow: /` (+ sitemap) |
| `DOMAIN.md` | Optional custom domain → Pages |

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

Pitch language matches product passport: Hermes L2 Suite / Near-Dup / advisory — not a fraud oracle.

## Discovery (B2B supplement)

- SEO meta + `sitemap.xml` + `robots.txt` on the Pages site  
- Frame the URL as **official product portal** in partner mail (`sdk/v2_suite/poc_suite/PARTNER_OUTREACH.md`)  
- Optional custom domain: see `DOMAIN.md` (additive; github.io remains valid until CNAME)
