# Shikha Murali — Cinematic Portfolio

A single-file, dependency-free portfolio site with a 3D particle universe that
morphs through six formations as you scroll. Designed and built by
[Kristom Robert](https://github.com/captainrobert07).

**Live:** https://shikha-vert.vercel.app

## What's in here

- A 28,000-particle GPU system in **Three.js** (custom GLSL vertex + fragment
  shaders, additive blending, depth fade, mouse repulsion).
- Six formations: globe, lattice, orbits, crystal, cosmos, helix — each
  triggered by `ScrollTrigger` as you scroll past a section.
- **Lenis** smooth scrolling so the morphs feel filmic, not jittery.
- **GSAP** timelines for character-level hero reveals, magnetic buttons,
  card tilts, animated counters, and word-by-word manifesto scrub.
- Custom blend-mode cursor with hover-state inflation.
- No framework, no bundler, no build step. Open `index.html` and you're in.

## Stack

| Layer                 | Choice                                             |
|-----------------------|----------------------------------------------------|
| Rendering             | Three.js 0.161 (ESM via importmap)                 |
| Smooth scroll         | Lenis 1.0                                          |
| Animation             | GSAP 3.12 + ScrollTrigger                          |
| Type                  | Instrument Serif · Inter · JetBrains Mono          |
| Hosting               | Vercel (static, auto-deploy from `main`)           |

## Local preview

```bash
start index.html
# or
python -m http.server 5173
```

## Deploy

Vercel is wired to this repo's `main` branch. Push and it deploys —
no build settings needed (`vercel.json` only sets security headers).
