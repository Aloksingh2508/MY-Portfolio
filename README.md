# Alok Singh — Portfolio

Interactive developer portfolio: Python developer · AI/ML enthusiast · Computer Science engineer (2026).

**Live:** https://aloksingh2508.github.io/MY-Portfolio/

## Features
- Cinematic loader and scroll-driven storytelling (GSAP ScrollTrigger + Lenis smooth scroll)
- Background sky that changes with the visitor's local time: morning, evening, night
- Optional AI voice guide (browser text-to-speech), off unless the visitor chooses it
- Project scenes with tilt/parallax, AI skill map, animated terminal
- Achievements section, resume sheet with PDF download, custom cursor, responsive layout

## Run locally
Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```

## Deploy on GitHub Pages
1. Push this folder to a GitHub repository.
2. Repository **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, folder = `/ (root)`.
3. Wait a minute, then open the URL shown on that page.

## Customize
Contact links and other details are at the top of the script in `index.html` (the `C` object). Everything is a single self-contained file that loads GSAP and Lenis from public CDNs.
