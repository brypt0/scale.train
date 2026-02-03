# Scale Trainer

An interactive web app for learning and practicing musical scales with MIDI keyboard support.

## Features

- **51 scales** across 8 categories (Major Modes, Minor Variants, Pentatonic, Blues, Symmetric, Dominant/Jazz, Bebop, World/Exotic)
- **MIDI keyboard support** - plug in any MIDI controller and play
- **Clickable piano** with sound - no MIDI? Click the keys to hear and practice
- **Quiz mode** - structured (by category) or random practice with progress tracking
- **Scale theory reference** - parent scale families, modal relationships, brightness spectrum
- **Full metadata** for each scale - step patterns, scale degrees, mood, fun facts, common uses

## Usage

**Online:** Visit the hosted version (if enabled via GitHub Pages)

**Local:** Download and open `index.html` in Chrome or Edge (required for Web MIDI API)

## Files

- `index.html` - Main trainer with piano, scale browser, and theory reference
- `quiz.html` - Quiz mode for testing your scale knowledge

## Tech

- Vanilla HTML/CSS/JS (no build step)
- [Tone.js](https://tonejs.github.io/) for piano audio (Salamander samples)
- Web MIDI API for keyboard input

## License

🄯 Copyleft 2026 Remikun Arbitrage

Free to use, modify, and redistribute.
