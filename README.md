# FLIPGATE v2026 - Game Script Utility 2026

> **A one-key gravity-flip game for the web.** Designed for fast, single-button play in an endless runner format using HTML5 canvas.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/matt-walker55/flipgate-web-game-script?style=flat-square)](https://github.com/matt-walker55/flipgate-web-game-script)

---

<p align="center">
  <a href="https://matt-walker55.github.io/flipgate-web-game-script/">
    <img src="https://img.shields.io/badge/Download-FLIPGATE%20Script-brightgreen?style=for-the-badge" alt="Download FLIPGATE Script">
  </a>
</p>

> **[Direct Download - FLIPGATE](https://matt-walker55.github.io/flipgate-web-game-script/)**

---

[Download Latest Build](https://matt-walker55.github.io/flipgate-web-game-script/)

---

## What it is

FLIPGATE is a browser game built around a single action: press one key to invert gravity and keep moving. It aims for short, replayable sessions where success depends on timing, reading obstacles ahead, and maintaining control through an endless runner loop. Rendering is handled with HTML5 canvas, while the gameplay logic is implemented in vanilla JavaScript.

The game also includes procedurally created obstacles, audio that plays in the browser, and feedback effects like particles and screen shake. A saved high score keeps progress between sessions, so players can jump back in and try to beat their previous result.

## Script Features

- Single-key gravity flipping controls
- Endless runner style gameplay loop
- Procedural obstacle spawning
- Persistent high score tracking
- Sound effects generated in the browser with WebAudio
- Particle effects for impact and motion feedback
- Screen shake for stronger visual response
- Zero-dependency implementation in vanilla JavaScript

## Getting Started

FLIPGATE is delivered as a browser-based HTML project. To run it locally, download the repository files, put them in a folder on your machine, and open the main HTML file in a modern browser.

Basic local usage:

1. Download the project files.
2. Keep the HTML, script, and asset files in the same directory.
3. Open the main page in your browser or serve the folder with any simple static host.

If you are packaging it for a site, upload the full folder structure so the canvas, script, and browser audio behavior load correctly.

## Options

The main gameplay and presentation settings can be edited directly in the JavaScript source. Common control points and configuration items include:

| Setting | Purpose |
| --- | --- |
| `SPACE` / primary key | Flip gravity during play |
| Audio toggle | Enable or disable generated sound effects |
| Effects toggle | Turn particles and shake on or off |
| Difficulty pacing | Tune obstacle generation speed |
| Score storage | Keep or reset the saved high score |

Example control flow:

    press key -> gravity flips -> avoid obstacles -> continue the run

## Compatibility

FLIPGATE is built for modern web browsers with support for HTML5 canvas and WebAudio. Since it uses vanilla JavaScript, there are no extra frameworks or packages to install.

Known considerations:

- Best suited for current desktop and mobile browsers
- Requires browser support for canvas rendering and audio generation
- Persistent score storage depends on browser storage availability
- Visual effects may vary by device performance

## FAQ

**How do I begin playing?**  
Open the project in a browser and use the primary key to flip gravity during the run.

**Can I change the game without reorganizing the files?**  
Yes. Most edits can be made in the HTML or JavaScript files while keeping the same folder layout.

**Where is progress saved?**  
The high score is stored persistently in the browser, while other options are usually controlled in the source files.

**Will it run in every browser?**  
It is targeted at modern browsers that support HTML5 canvas and WebAudio. Older browsers may not handle all effects correctly.

**Can the gameplay be customized?**  
Yes. Difficulty, visuals, audio behavior, and controls can be adjusted in the code.

**Are there any dependencies to install?**  
No. The project is built with zero dependencies.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
