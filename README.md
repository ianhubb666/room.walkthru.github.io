# Room 3D Tour

An interactive 3D bedroom walkthrough built with Three.js — no frameworks, no build tools, just three HTML files.

## Live Demo

> After enabling GitHub Pages, your URL will be:
> `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME`

## Features

- **Walk Mode** — WASD to move, mouse to look around (desktop) / virtual joystick (mobile)
- **Orbit View** — drag to rotate, scroll/pinch to zoom
- **Move Furniture** — click/tap and drag to reposition the desk, bed, chair, and doors
- **Top-down Plan** — bird's-eye floor plan view
- **Transparent Walls** — walls are opaque from inside, ghosted from outside so you can see the layout
- **Responsive** — auto-detects mobile and loads touch-optimised controls

## Files

| File | Description |
|------|-------------|
| `index.html` | Landing page — auto-detects device and redirects |
| `desktop.html` | Full 3D experience with keyboard + mouse controls |
| `mobile.html` | Touch-optimised version with virtual joystick |

## Deploy to GitHub Pages

1. Fork or upload this repo to GitHub
2. Go to **Settings → Pages**
3. Set **Source** to `main` branch, `/ (root)` folder
4. Click **Save**
5. Visit `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME`

## Room Dimensions

- Room: 12ft 6.69" × 9ft 1.22" (150.69" × 109.02")
- Closet: 20.47" deep × full left wall length
- Bed: 80" × 60" (queen), headboard on right wall
- Desk: 60" × 30", back wall

## Built With

- [Three.js r128](https://threejs.org/) — loaded via CDN, no install needed
