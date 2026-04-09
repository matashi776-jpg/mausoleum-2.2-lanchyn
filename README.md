# Mausoleum 2.2: Lanchyn — playable first slice

A clean Vite + Phaser TypeScript repo for a 12-room first slice.

## What is included
- 12 connected rooms
- 2 switchable heroes at shrines
- 3 enemy types
- 1 boss encounter in room 12
- checkpoints + local save
- pause, game over, and victory scenes
- runtime-generated placeholder visuals, so the game runs without external art files

## Controls
- Move: Left / Right
- Jump: Space or Up
- Attack: Z or X
- Interact with shrine: E
- Pause: Esc

## Run locally
```bash
npm install
npm run dev
```

## Production build
```bash
npm run build
npm run preview
```

## GitHub Pages note
This repo is structured like a standard Vite app. If you deploy under a subpath, set `base` in `vite.config.ts` before building.

## BlueStacks note
This project is a web game. The practical path is:
1. run locally in a browser
2. publish to GitHub Pages or another static host
3. open the published URL inside a browser in BlueStacks if you want Android-style testing
