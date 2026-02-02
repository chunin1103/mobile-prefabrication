# Mobile PreFab Landing Page

## Project Overview
Static landing page for Mobile PreFab — a mobile MEP prefabrication service. Woman-owned business. Deployed via GitHub Pages to https://mobile-prefab.com.

## Tech Stack
- Single-page static site (`index.html`)
- Tailwind CSS via CDN (`cdn.tailwindcss.com`)
- Inter font via Google Fonts
- No build step or framework

## Structure
- `index.html` — entire site (landing page with hero video, solution cards, credibility section, Tally contact form)
- `assets/favicon.png` — browser tab favicon (M icon)
- `assets/mobile-prefab-logo.png` — full logo used for OG/social media images
- `video/hero-video.mp4` — hero background video (compressed, ~2MB)

## Brand
- Primary green: `#03c988`
- Dark blue (text): `#00337c`
- Font: Inter

## Deployment
- Hosted on GitHub Pages, pushes to `main` deploy automatically
- Domain: mobile-prefab.com
- `CNAME` file is required in repo root for custom domain — do not delete it

## Notes
- Hero video was compressed from 13MB to ~2MB using ffmpeg (CRF 26, preset slow, no audio). Original was 20Mbps bitrate which was excessive for web.
- Favicon uses `assets/favicon.png` (M icon); social media OG/Twitter images use `assets/mobile-prefab-logo.png` (full logo)
- Solution cards: "Increase Installation Rates", "Smaller Crews, Less Overhead", "Expert Operator"
