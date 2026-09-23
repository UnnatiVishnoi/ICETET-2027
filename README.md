# ICETET-2027 (Static HTML copy)

Plain HTML version of the ICETET-2027 conference website — same design and
content as the React version. No build step, no npm required.

## View it

Option 1 — local server (recommended, full interactivity):

```sh
cd ICETET2027-HTML
python3 -m http.server 8080
```

Then open http://localhost:8080

Option 2 — open `index.html` directly in a browser. Content is readable,
but interactive features (menu, slider, countdown) need Option 1.

## Deploy

Upload the contents of this folder to any static host
(GitHub Pages, cPanel `public_html`, Netlify, Vercel).

## Pages

index.html, about.html, call-for-papers.html, important-dates.html,
committee.html, registration.html, contact.html (+ 404.html fallback).

## Refreshing this copy

Re-generated from the React project with:

```sh
node ./scripts/snapshot-html.mjs   # run from ICETET2027 with preview on :4174
```
