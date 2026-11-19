# ENORME — THE CODEBLASTERS

Play the Commodore 64 production **ENORME** by **THE CODEBLASTERS** directly in your browser.

**[Launch the C64 web version](https://serigrafiamdp-web.github.io/ENORME-THE-CODEBLASTERS/)**

## About

This repository hosts the web-player version exported from LVLLVL. The actual C64 program is embedded in `js/content.js`, and it starts in the browser's C64 emulator.

- `index.html` — page and canvas
- `js/content.js` — C64 program and player configuration (original ZIP)
- `js/c64.min.js`, `js/c64.wasm` — compatible C64 emulator runtime from [LVLLVL](https://github.com/jaammees/lvllvl)
- `images/` — virtual keyboard and joystick graphics, from LVLLVL
- `.github/workflows/deploy-pages.yml` — automatic GitHub Pages deployment

Keyboard input is available on desktop. Mobile controls are enabled. Audio may require interaction with the page depending on your browser.

## Deployment

Pushing changes to `main` automatically triggers GitHub Pages deployment. The static site needs no server or external backend.

## Acknowledgment

Web C64 emulator assets: [James / LVLLVL](https://github.com/jaammees/lvllvl). C64 production credit: **THE CODEBLASTERS**.
