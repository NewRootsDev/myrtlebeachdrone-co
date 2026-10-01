# myrtlebeachdrone.co

Single-page local landing site for New Roots Development, LLC, served by GitHub Pages at `https://myrtlebeachdrone.co/`.

- `index.html` is the whole site. No external scripts, no stylesheets, no build step.
  The one network call it makes is the contact form's, and only when a visitor
  submits: it mints an anonymous Wix visitor token and posts one submission to the
  Wix form "Local Site Inquiry". The client id in the page is public and
  visitor-facing by design; it mints anonymous tokens and nothing else.
- `CNAME` binds the custom domain. Do not delete it; Pages drops the domain if it goes.
- `robots.txt` and `sitemap.xml` are static. Update `lastmod` in the sitemap when `index.html` changes.
- Copy rules: no em dashes, no employer names, no command counts, posted prices only as they appear in `nrd/canonical-figures.md`, Autodesk marks as adjectives followed by a noun. See the NRD project `nrd/conventions.md`.

Generated 2026-09-27 by `build.py` in the NRD sites kit. Edit `index.html` directly or regenerate from the kit; either is fine, but do not do both without merging.

## Where git keeps its data (since 2026-10-01)

`.git` in this folder is a one-line pointer FILE, not a folder. The git database lives outside
the synced folder at `C:\Users\chris\Documents\GitHub\_gitdirs\myrtlebeachdrone-co.git`.
Proton Drive syncs all of `NRDClaude`, and a sync name clash can rename git's `index` file,
which makes git show every tracked file as deleted (it happened to the Website repo on
2026-10-01). Every git command still runs from this folder as before. Do not delete the `.git`
file and do not move that folder. If `.git` is ever missing or renamed, recreate it with one
line: `gitdir: C:/Users/chris/Documents/GitHub/_gitdirs/myrtlebeachdrone-co.git`.
