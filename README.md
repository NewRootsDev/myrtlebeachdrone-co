# myrtlebeachdrone.co

Single-page local landing site for New Roots Development, LLC, served by GitHub Pages at `https://myrtlebeachdrone.co/`.

- `index.html` is the whole site. No external scripts, no stylesheets, no build step.
  The one network call it makes is the contact form's, and only when a visitor
  submits: it mints an anonymous Wix visitor token and posts one submission to the
  Wix form "Local Site Inquiry". The client id in the page is public and
  visitor-facing by design; it mints anonymous tokens and nothing else.
- `CNAME` binds the custom domain. Do not delete it; Pages drops the domain if it goes.
- `robots.txt` and `sitemap.xml` are static. Update `lastmod` in the sitemap when `index.html` changes.
- Copy rules: no em dashes, no employer names, no command counts, no posted prices, Autodesk marks as adjectives followed by a noun. See the NRD project `nrd/conventions.md`.

Generated 2026-09-21 by `build.py` in the NRD sites kit. Edit `index.html` directly or regenerate from the kit; either is fine, but do not do both without merging.
