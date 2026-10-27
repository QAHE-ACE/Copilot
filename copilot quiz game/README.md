# Copilot Knowledge Challenge

A guidebook plus two games about Copilot Notebooks, by ACE Team. Everything is static (no build step).

| Path | What it is |
| --- | --- |
| `/` (`index.html`) | The step-by-step guidebook |
| `/game/` | 3D adventure game "Copilot Knowledge Challenge" (ragdoll cat) |
| `/game-2d/` | 2D escape-room version of the game |

The game's final screen links to the guidebook (`../`), and the guidebook has a "Play the game" button (`game/`).

## Deploy to GitHub Pages
1. Create a repository and upload everything in this folder (keep the folder structure).
2. Settings > Pages > Deploy from a branch > `main` / root > Save.
3. Open `https://<your-username>.github.io/<repo-name>/` after about a minute.

## Run locally
Open `index.html` or `game/index.html` in a browser (internet needed for three.js and Google Fonts), or run `python3 -m http.server` here and visit http://localhost:8000/

## Theme and branding
- Theme colour: tangerine `#F28500` (text variant `#B85600` for readability). Look for `--accent` (guidebook) and `--violet` (games) in the CSS.
- Logo and copyright: "ACE Team" in Montserrat ExtraBold, tangerine (`.logo` class).

&copy; 2026 ACE Team. All rights reserved.
