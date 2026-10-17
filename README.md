# Jollof Catch

A fast-paced arcade game built for [start.ng](https://start.ng).

## How to Play
- **Controls**: Slide left and right using touch/mouse drag, horizontal arrows, or `A` / `D` keys.
- **Goal**: Catch falling plates of delicious jollof rice (🍛), crispy chicken (🍗), and sweet plantains / dodo (🍌).
- **Special Drop**: Catch the chilled drink (🥤) to cool down 1 burn and earn +3 bonus plates!
- **Dodge**: Avoid the fiery scotch bonnet peppers / Ata Rodo (🌶️). 3 burns and the round ends!
- **Pause**: Press `Esc` or tap the ⏸️ pause button at any time.

## Features
- **Instructions & Guide**: Built-in How to Play modal with item breakdown and gameplay tips.
- **Custom Settings**:
  - Sound effects toggle with custom real-time Web Audio synthesizer (no external audio files required).
  - Haptic vibration feedback for mobile devices.
  - Screen shake & particle effects toggle.
  - Control responsiveness adjustment (Smooth lerp vs Snappy direct follow).
  - Persistent settings stored in `localStorage`.
- **Visual Polish**:
  - Reaction animations: Characters celebrate on catches and grimace with smoke when burned.
  - Particle bursts for catches, burns, and chilled drinks.
  - Floating combo / streak numbers and "Party Fever" aura when reaching high streaks.
- **Start.ng Integration**:
  - Dynamic character customization directly reflecting the player's start.ng avatar, skin tone, hair style, clothing colors, hat, and accessories.
  - Guest mode with instant fallback look and sign-in prompt.
  - Live shared leaderboard tracking two verified stats: **Plates caught** and **Best streak**.
- **100% Static & Standalone**: Pure HTML5 Canvas, modern CSS, and JavaScript with relative paths and zero external libraries or network CDNs.
