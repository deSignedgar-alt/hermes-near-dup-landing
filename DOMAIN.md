# Custom domain for Hermes L2 Suite landing (optional, B2B trust)

Current public URL (works today):

https://designedgar-alt.github.io/hermes-near-dup-landing/

`username.github.io/repo/` is fine for engineers; procurement often prefers a short brand host
(e.g. `hermes-verify.io` or your chosen name).

## Steps (no code delete — additive)

1. Register the domain with your registrar.  
2. In repo **deSignedgar-alt/hermes-near-dup-landing** → Settings → Pages → Custom domain.  
3. Add DNS:
   - Apex: `A` records GitHub Pages IPs (per current GitHub docs), or  
   - `www` / subdomain: `CNAME` → `designedgar-alt.github.io`  
4. Commit a root file `CNAME` on `gh-pages` containing only the hostname (e.g. `hermes-verify.io`).  
5. Enable “Enforce HTTPS” after DNS propagates.  
6. Update canonical / sitemap / outreach links to the new host.  
7. Google Search Console → add property → Request Indexing for `/` and `/trust.html`.

Until the domain is chosen, keep shipping the github.io portal URL framed as **official product portal** in mail (see `PARTNER_OUTREACH.md`).
