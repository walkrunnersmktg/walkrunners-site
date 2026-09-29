# Walkrunners construction site

A small, static coming-soon page based on the Walkrunners "Paper & Ink" rebrand direction.

## Files

- `index.html` — page markup and tiny amount of vanilla JavaScript
- `styles.css` — responsive brand styling
- `assets/walkrunners-logo.png` — supplied Walkrunners logo artwork

## Contact links

The launch links are configured as follows:

- **Connect with us** → `mailto:chris@walkrunners.com`
- **Schedule time** → `https://calendly.com/chris-walkrunners`
- The client-login link has been removed for now.

## Preview locally

You can double-click `index.html`, or run a simple local server from this folder:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy

This folder is static and can be deployed as-is to Netlify, Cloudflare Pages, Vercel, GitHub Pages, or any standard web host. No build step or framework is required.

## Typography

The stylesheet uses Georgia as a license-safe display-serif fallback and Inter/system sans-serif for body copy. If you have licensed Canela, GT Sectra, or Söhne webfont files, add them under `assets/fonts/` and replace the font variables at the top of `styles.css` with `@font-face` declarations.

## Domain launch notes

The domain registrar is GoDaddy. Publish and test this site at the hosting provider's preview URL first. Only after the preview is approved should the DNS records for `walkrunners.com` / `www.walkrunners.com` be changed in GoDaddy to the values supplied by the chosen hosting provider. Keep the existing email-related DNS records (MX, SPF, DKIM, and DMARC) intact unless your email provider explicitly instructs otherwise.
