# Epic Adventure

A two-level 2D platformer built from scratch in vanilla JavaScript and the HTML5 Canvas API — no game engine, no framework, no build step.

## Features

- Bilingual (Arabic/English) landing page introducing the game
- **Level 1 — Platform Adventure:** a classic side-scrolling platformer with a 5-heart life system, collectible coins, and enemies to avoid or jump past
- **Level 2 — desert endless runner:** dodge cacti while a live score counter climbs, styled as a night desert scene
- Login/register flow with a Super Mario World-themed UI
- Game over screen

## Tech stack

Vanilla JavaScript, HTML5 Canvas, CSS — no dependencies, no package manager.

Art assets: Kenney's ["Platformer Art Pixel Redux"](https://www.kenney.nl/assets/platformer-art-pixel-redux) pack (CC0 1.0).

## Getting started

No install step needed — just open `index.html` in a browser, or serve the folder with any static file server:

```bash
npx http-server .
```

## What I'd improve

- The login/register flow currently points at a mock API service that's no longer available — replace it with either a lightweight real backend or a local-storage-only guest flow so accounts persist reliably
- Add a proper game-over/restart flow tying level completion back to the landing page
- Split `game.js` (1000+ lines) into smaller modules (player, enemies, collision, rendering) as the game grows

## Team

Originally built by:

- **[Intisar Alosaimi](https://github.com/EntisarOsiami)**
- **[Saad F. Alzarea](https://github.com/SaadAlzarea)**
- **[khaled almutairi](https://github.com/g39g1)**
- **[shahad0000](https://github.com/shahad0000)**
