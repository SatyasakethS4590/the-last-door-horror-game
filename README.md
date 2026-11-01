# THE LAST DOOR

A first-person mystery-horror browser prototype with a three-floor, 25-room mansion, five family memories, distinct ghost behaviours, flashlight, wardrobe hiding, a case file, and an archive puzzle.

## Run locally
Serve this folder from a local web server (for example, `python -m http.server 8000`) and open `http://localhost:8000`. The Three.js module is loaded from a CDN, so an internet connection is needed on first load.

## Controls
- **WASD** — move
- **Mouse** — look around
- **E** — interact with memories, wardrobes, stairs, key, and archive door
- **1, 2, 3** — enter the study puzzle sequence
- **F** — flashlight
- **J** — family case file
- **Esc** — release mouse (click the game to resume)
- **Touch devices** — use the on-screen direction/action buttons; drag the scene to look around

## Archive puzzle
Read the inscription in the library. It hints at the sequence **2, 1, 3**. Enter that sequence while near the study lock, collect the key from the study, then use it at the locked archive door on the top floor.

Progress for collected memories, puzzle completion, archive key, and archive door unlock is saved in this browser. Ambient sound and heartbeat effects start after entering the mansion.

This is an early playable prototype, not the complete planned 7–9 hour game. Full browser playtesting and further level design are still needed.
