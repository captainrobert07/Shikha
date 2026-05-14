# Shikha Murali — Personal Site

A single-file, dependency-free landing page for Shikha Murali (Business Intelligence
Developer & People Manager). Cinematic video hero, liquid-glass nav, and sections
covering about, skills, and certifications.

## Stack

- Plain HTML + CSS + JS
- Tailwind CSS via CDN
- GSAP (CDN) for the mouse-parallax video background
- Lucide icons (CDN)
- Google Fonts: Inter, Instrument Serif, Barlow

No build step. Open `index.html` directly in a browser, or deploy as static.

## Local preview

Just open the file:

```
start index.html
```

Or serve it with any static server (Python comes bundled with one):

```
python -m http.server 5173
```

Then visit http://localhost:5173.

## Deploy to Vercel

This repo is a static site — Vercel needs no build settings.

1. Push this folder to a GitHub repository.
2. On https://vercel.com/new, import the repository.
3. Framework preset: **Other**. Build command: leave blank. Output directory: leave blank.
4. Deploy.

`vercel.json` already sets sensible security headers.
