# Neon Borough 🌆

A colorful, New York-inspired 3D city-building browser game powered by Three.js.

## Features
- Procedural skyscrapers, offices, and homes
- Manhattan-style street grid with moving traffic
- Build towers, offices, homes, parks and roads; demolish lots
- Budget, population, passive income
- Orbit, pan, and zoom camera controls
- Adjustable day/night cycle

## Run locally
Serve the repository directory over HTTP, for example:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

Three.js loads from jsDelivr, so internet access is required.

## Controls
- Left click: build/demolish
- Left drag: orbit
- Right drag: pan
- Scroll: zoom
- 1–6: select tool
- Space: pause/resume day/night

## Deploy to Vercel
Import this GitHub repository into Vercel. Select **Other** as framework, leave build and install commands blank, and set output directory to `.`. Vercel will deploy `index.html` as a static site.

## Notes
Road placement is visual; traffic follows the original grid. City state is not persisted after refreshing the page.
