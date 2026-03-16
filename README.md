# Ratali

Ratali is a customized offline runner game based on the Chromium Dino game codebase.

## Features

- Safari-compatible immediate retry by keystroke after crash
- Custom crash audio playback from `dino/sounds/Trump.mp3`
- Mobile control buttons and touch-friendly behavior
- Umami analytics integration

## Project Structure

- `dino/`: Game source, runtime bundle, HTML/CSS assets
- `dino/dino_game/`: TypeScript game logic source
- `dino/game.js`: Built runtime script used by the page
- `dino/neterror.html`: Main game page and runtime customizations

## Run and Build

From the repository root:

```bash
node build.mjs
```

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
