# Aura Visualizer 🔥

A minimal, zero-dependency browser-based circular audio visualizer built with **HTML5 Canvas**, **Vanilla JavaScript**, **Tailwind CSS**, and the **Web Audio API**. Inspired by modern UI design systems, **Aura Visualizer** renders 360° frequency spectrum rays with real-time audio capture and soft ambient color palettes.

![Aura Visualizer](https://img.shields.io/badge/Status-Active-brightgreen) ![License](https://img.shields.io/badge/License-MIT-blue) ![Dependencies](https://img.shields.io/badge/Dependencies-Zero-success)

## ✨ Features
- **360° Spectrum:** Uses logarithmic frequency bin mapping and O(1) bilateral mirroring to create balanced, aesthetically pleasing circular frequency rays.

- **Multiple Audio Sources:**
  - **System Audio:** Captures desktop or browser-tab audio (YouTube, Spotify Web, SoundCloud) using the Media Capture / Screen Capture API.
  - **Microphone Input:** Routes live microphone or line-in audio through the Web Audio `AnalyserNode`.
  - **Demo Synth:** Built-in Web Audio synthesis loop to test high-energy visuals without needing external audio playing.
- **Color Palettes & Dark Mode:**
  - Three soft gradient themes: ***Sky Mist***, ***Lavender Dusk***, and ***Mint Breeze***.
  - Full light/dark mode support with dynamic gradient switching.
- **Razor-Sharp Rendering:** Automatically scales for Retina and 4K displays using `devicePixelRatio`.
- **Compression & Smoothing:** Integrated noise-gate filtering (`14/255` threshold) and exponential amplitude response to eliminate visual jitter and prevent frequency clipping.

## 🚀 Getting Started
### Quick Start (No Installation Required)

1. Clone or download this repository:
   ```bash
   git clone https://github.com/Zain-R98/Aura-Visualizer.git 
   ```
2. Open `index.html` in any modern web browser (Google Chrome, Microsoft Edge, Brave, or Opera recommended for system audio capture support).

## License

This project is open-source and available under the [MIT License](LICENSE).
