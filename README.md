# AI Pose Reference Gallery

A clean, English-language web gallery for browsing **1,439 AI pose reference images** (288 unique poses with multiple angles).

These are faceless gray mannequin line drawings designed as reference for AI image generation (Stable Diffusion, Flux, Midjourney, etc.). Simply use the pose image as a reference and prompt “change to this pose” or use it with ControlNet / IP-Adapter.

## Source

- Original free database by [@giaaibusi](https://x.com/giaaibusi)
- Explicitly released as free, commercial use OK, editing & secondary use OK
- Community mirror & images: [anhao/ai-pose-gallery-zh](https://github.com/anhao/ai-pose-gallery-zh)

## Features

- Filter by system (Full Body Sexy / Standard, Upper Body, Couple)
- Filter by classification and viewing angle
- Search by pose name
- Lightbox with full-size PNG download
- Responsive & fast

## Local Use / GitHub Pages

1. Clone this repo
2. Serve with any static server (e.g. `python -m http.server`)
3. Or enable GitHub Pages on the `main` branch

The images are loaded from the public community mirror on GitHub so the site works immediately.

## Files

- `index.html` — the gallery app
- `poses-en.json` — English metadata for all 1,439 entries

## License Note

The pose images and original data remain the work of the original author. This repository only provides an English frontend and metadata. Use responsibly and respect the original free-use terms.
