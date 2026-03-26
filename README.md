# Pixel Survivors

A pixel-art vampire survivors-style game built as a single HTML file. Playable as a PWA.

## Play

Open `index.html` in your browser, or visit the [live version](https://alchemicalretard.github.io/PixelKiller/).

## Controls

- **WASD / Arrow Keys** — Move
- **D-Pad** — Mobile touch controls
- Weapons fire automatically

## Weapons (12)

| Weapon | Description |
|--------|-------------|
| Sword | Melee swing at nearest enemy |
| Magic Orb | Homing projectile |
| War Axe | Orbits around the player |
| Lightning | Piercing bolt in random direction |
| Garlic | Passive damage aura |
| Daggers | Fast projectiles in facing direction |
| Holy Water | Damaging pool on enemies |
| Boomerang | Thrown projectile that returns |
| Fire Ring | Expanding ring of fire |
| Shuriken | Stars thrown in all directions |
| Meteor | Random AoE explosions from the sky |
| Chain Bolt | Lightning that bounces between foes |

## Enemies

- **Slime** — Slow, basic enemy
- **Bat** — Fast, fragile flyer (after 60s)
- **Skeleton** — Tough melee fighter (after 120s)
- **Demon** — Tanky boss-type (after 200s)

## Features

- Single HTML file, zero dependencies
- Installable PWA (offline support)
- Mobile-friendly with touch D-Pad
- Pixel art retro style
- Sound effects via Web Audio API
- Level-up system with weapon upgrades

## Files

- `index.html` — The entire game
- `manifest.json` — PWA metadata
- `sw.js` — Service worker (offline support)
- `icon-192.png` / `icon-512.png` — App icons
