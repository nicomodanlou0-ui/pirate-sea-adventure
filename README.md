# Pirate Sea Adventure 🏴‍☠️

A simple **browser-based 3D pirate sailing prototype** made with Three.js.

You control a pirate ship on an open ocean. Use the controls below to sail around.

This is a **starter project** — not a full game. You can expand it with islands, combat, treasure, multiplayer, better graphics, etc.

## How to play

1. Open `index.html` in a modern browser (Chrome, Firefox, Edge).
2. Or serve it locally:
   ```bash
   # if you have Python
   python -m http.server 8000
   # then go to http://localhost:8000
   ```

### Controls
- **W / ↑** : Sail forward
- **S / ↓** : Sail backward
- **A / ←** : Turn left
- **D / →** : Turn right
- **Mouse** : Look around (optional)

## Features included
- Procedural ocean with simple wave animation
- Basic pirate ship (hull + mast + sail)
- Third-person camera that follows the ship
- Daytime lighting + sky
- Infinite-feeling open sea

## Next steps you can take
- Add islands with trees and treasure chests
- Better water shader (look up Three.js water examples)
- Enemy ships and cannons
- Inventory / gold system
- Sound effects and music
- Switch to Godot or Unreal for higher graphics quality later

## Tech
- Three.js (r160+ via CDN)
- Pure HTML + JavaScript — no build step required

Have fun sailing the high seas, captain!
