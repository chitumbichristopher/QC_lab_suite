# Smart QC Lab Suite & Learning Hub

A browser-based toolkit for pharmaceutical Quality Control analysts — calculators (assay %, Karl Fischer water content, %RSD, manual/liquid-dilution), volumetric solution preparation & standardization reference, a 13-instrument SOP directory, a full instrument troubleshooter, a categorized pharma/chemistry quiz, regulatory links, and a visitor Q&A board.

Live at: `https://<your-github-username>.github.io/<repo-name>/` once GitHub Pages is enabled (see below).

## Developed by

**Christopher Chitumbi** — Quality Control Analyst
Zenufa Laboratories Ltd, P.O. Box 3230, Ilala, Dar es Salaam, Tanzania
Email: christopherchitumbi171@gmail.com

## Running locally

This is a single self-contained HTML file (Tailwind CSS loaded from CDN, no build step required). Just open `index.html` in any browser.

## Publishing with GitHub Pages

1. Push this repo to GitHub (see commands below).
2. Go to your repo on GitHub → **Settings → Pages**.
3. Under "Build and deployment", set **Source** to `Deploy from a branch`.
4. Choose branch `main`, folder `/ (root)`, then **Save**.
5. GitHub will publish it at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Using a custom domain (optional)

If you own a domain (e.g. `qclab.yourcompany.com`) and want the site to load from it instead of the default `github.io` address:

1. Create a file named `CNAME` (no extension) in the root of this repo containing just your domain, e.g.:
   ```
   qclab.yourcompany.com
   ```
2. At your domain registrar / DNS provider, add a **CNAME record** pointing that subdomain to `<your-username>.github.io`.
   - For an apex/root domain (e.g. `yourcompany.com` with no subdomain) instead, add **A records** pointing to GitHub Pages' IP addresses (185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153) instead of a CNAME.
3. Back in **Settings → Pages** on GitHub, enter the same domain under "Custom domain" and save. GitHub will verify it and can auto-provision HTTPS for you (may take up to 24 hours for DNS to propagate).

## License

All rights reserved unless you choose to add an open-source license.
