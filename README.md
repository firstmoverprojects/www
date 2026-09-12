# First Mover Projects — www

Permanent home base for [firstmoverprojects.com](https://firstmoverprojects.com), hosted on **free GitHub Pages**.

## Live URLs
- Custom domain (after DNS): https://firstmoverprojects.com
- GitHub Pages: https://firstmoverprojects.github.io/www/

## Pages
- `index.html` — hero, offers, social, CTA
- `partnerships.html` — Challenge Pilot / licensing (async B2B)
- `privacy.html` · `terms.html` · `refund.html`
- `CNAME` → `firstmoverprojects.com`

## DNS (Porkbun)
See `/workspace/hunts/os/domain-site-dns-2026-09-12.md` in the ops hunt log. **Do not change MX** (fwd1/fwd2 email forwards) or Brevo SPF/DKIM/DMARC.

## Deploy
Push to `main`; Pages source = `/` (root). Reversible: delete repo or disable Pages anytime.
