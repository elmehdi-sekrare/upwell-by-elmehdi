# Upwell by El Mehdi

Website for **Upwell**, a creative and paid media agency: one team that makes the ads and runs the paid social, search and SEO.
13 pages: home, work with 6 case studies, services, agency, contact (interactive audit form), privacy, terms and a 404 page.

Static build: HTML, CSS and JS with GSAP scroll animations, autoplay video stories, a cost calculator and a mobile menu sheet.
Self-hosted fonts and media, no third-party requests.

## Run locally
```bash
npm start        # http://localhost:5331
```
No install needed (Node 18+).

## Deploy on Netlify
Connect this repo in Netlify. `netlify.toml` already sets everything: publish directory `site`, no build command,
pretty URLs (`/work` → `/work/`), the 404 page, and cache headers.

## Structure
```
site/              the website (pages, /_astro scripts, /img, /video, /fonts)
scripts/serve.mjs  local server that behaves like Netlify
netlify.toml       Netlify settings
```

## Credits
Based on the Upwell template by [Visuvate](https://visuvate.com/). Contact details and branding by El Mehdi Sekrare
([LinkedIn](https://www.linkedin.com/in/el-mehdi-sekrare-77000629b) · [GitHub](https://github.com/elmehdi-sekrare)).
