# GlowSamer Aura

Premium landing page for **GlowSamer Aura** — an international OnlyFans and paid-content management agency.

## Stack

- Pure HTML / CSS / JavaScript (no framework dependencies)
- All assets embedded (base64 images, inline CSS/JS)
- Static site — no build step required

## Features

- Dark premium aesthetic with purple/lilac glow and glassmorphism
- Scroll-driven hero showcase with 7 creator video cards
- Coverflow carousel with autoplay, drag, keyboard navigation
- Animated metric counters and reveal-on-scroll effects
- Multilingual support: English (default), Portuguese, Spanish, Russian
- Language saved to `localStorage` and persisted across sessions
- Fully responsive: 320px → 1440px+
- Mobile-optimized header with hamburger menu and scroll lock
- `prefers-reduced-motion` support
- Security headers via `vercel.json`

## Deploy to Vercel

### Option 1 — Vercel Dashboard

1. Go to [vercel.com/new](https://vercel.com/new)
2. Import this repository (or drag the folder)
3. Deploy — no configuration needed

### Option 2 — Vercel CLI

```bash
npm i -g vercel
cd glowsamer-aura
vercel
```

### Option 3 — GitHub

1. Push this folder to a GitHub repository
2. Connect the repo to Vercel
3. Vercel auto-detects the static site and deploys

## Project Structure

```
glowsamer-aura/
├── public/
│   └── index.html      # Full landing page (HTML + CSS + JS + assets)
├── vercel.json          # Vercel deploy config + security headers
├── package.json         # Project metadata
├── .gitignore           # Git ignore rules
└── README.md            # This file
```

## Custom Domain

After deploying, add your domain in the Vercel dashboard:
**Settings → Domains → Add `glowsameraura.com`**

## License

Private — © 2026 GlowSamer Aura. All rights reserved.
