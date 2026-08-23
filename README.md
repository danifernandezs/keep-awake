# keep·awake

[![Website](https://img.shields.io/badge/Website-keepawake.dev-1a7f4b?style=flat-square)](https://keepawake.dev/) [![GitHub](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github)](https://github.com/danifernandezs/keep-awake) [![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC_BY--SA_4.0-blue?style=flat-square)](https://creativecommons.org/licenses/by-sa/4.0/) [![Zero dependencies](https://img.shields.io/badge/Zero-dependencies-1a7f4b?style=flat-square)](https://keepawake.dev/)

A free, single-page web tool that keeps your computer awake and prevents screen sleep or lock. No ads, no accounts, no cookies, no tracking. One open browser tab is all it takes.

**Try it: [keepawake.dev](https://keepawake.dev/)**

## How it works

- **Screen Wake Lock API** — while the tab is visible, the browser asks the OS not to dim, sleep or lock the screen. The lock is re-acquired automatically when you come back to the tab.
- **Silent audio fallback** — a 1-second WAV of true silence, generated in memory and looped. While it "plays", the system stays awake, even with the tab in the background.

## Usage

1. Open [keepawake.dev](https://keepawake.dev/).
2. Press **Start**.
3. Keep the tab open. Tip: park it in another window or a second browser and keep working in yours.

## What it is not

A web page cannot move your mouse cursor. If your presence tool requires real mouse or keyboard events, no static website can do that. Keeping the machine awake and unlocked is what keeps most tools (Teams included) from marking you away.

## Tech

One static HTML file. No framework, no build step, no external requests. Dark/light theme with `light-dark()` CSS. Deploys to GitHub Pages on every push to `main` via GitHub Actions.

## License

This work is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

Please read the [LICENSE](LICENSE.txt) file for more details.
