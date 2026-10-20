# Vrisama Ads — V4 Website + Social Campaign Studio

**Preview:** Open `index.html` in a modern desktop/mobile browser, then click **Ad scheduler**.

## Contents
- `index.html` — original violet/mint 3D homepage, accessibility + positioning updates, Work (in-house examples), About, FAQ and qualified WhatsApp contact
- `scheduler.html` — interactive draft campaign planner (Facebook/Instagram/Google/YouTube/LinkedIn; local browser storage; CSV export)
- `privacy.html` — transparent explanation of contact and local planner data
- `og-image.jpg`, favicons — social sharing image and browser identity
- `sitemap.xml`, `robots.txt`, `CNAME` — publishing assets for ads.vrisama.in

## Important distinctions
- Campaign Studio **does not publish, schedule or purchase live ads**. It only plans drafts.
- Project examples on the site are **in-house prototypes**, not paid client case studies or verified performance results.
- WhatsApp/email/phone use verified contact details supplied for Vrisama. A custom domain mailbox is not yet configured.
- CTA data attributes and local event hooks are installed, but **no analytics platform is connected**. No visitor tracking report is available yet.
- No pricing figures, testimonials or guaranteed results have been invented.
- Site is **not published** by these files alone.

## GitHub Pages launch checklist
1. Create a **separate** repo for `ads.vrisama.in`; do not overwrite the existing `aicareers.vrisama.in` repo.
2. Upload all production files from this folder at repo root.
3. Settings → Pages → Deploy from branch `main` / `root`.
4. Set custom domain to `ads.vrisama.in` (CNAME file included).
5. In Vrisama's DNS, add **CNAME** record: host `ads`, target `mjeenugara9663.github.io` (assuming same GitHub Pages owner, verify before changing DNS).
6. After DNS and TLS provisioning, enable Enforce HTTPS.
7. Confirm https://ads.vrisama.in, /scheduler.html, /privacy.html, /og-image.jpg, favicon and sitemap load.
8. Test WhatsApp/email/phone and planner create/edit/delete/export on desktop and Android/iPhone.
9. Run Lighthouse and axe on the actual live site; seek good results but don't claim 100 before testing.
10. Verify Search Console; confirm WhatsApp/LinkedIn OG previews.

## Next decisions requiring owner input
- Actual verified client case studies and permission to publish them
- Founder bio/photo, exact commercial packages/prices and delivery timelines
- Vrisama domain mailbox (e.g. hello@vrisama.in), once created
- Analytics vendor and privacy requirements if measuring site-wide CTA clicks
- Authenticated Meta/Google APIs + backend for future automatic publishing