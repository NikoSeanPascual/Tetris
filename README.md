# Niko's Tetris

A modern, highly optimized desktop Tetris clone built using Python and Pygame. Featuring smooth animations, dynamic color transitions, audio management, and a sleek retro-arcade aesthetic.

Commissioned by **Aron** | Developed by **Niko Sean Pascual**

---

## 🚀 Features

* **Optimized Engine Performance:** Custom asset pre-rendering handles resource-intensive calculations (like real-time glow and bloom effects) before the main loop starts, ensuring a locked 60 FPS.
* **Dynamic Visuals & Effects:** Implements chromatic aberration (RGB split) title styling, dynamic color-fading background transitions, and a custom CRT arcade screen overlay filter.
* **Smart Mechanics Fixes:** Features an updated downward collision handling architecture to eradicate the classic "ledge slide lock" bug, ensuring seamless piece sliding off platforms.
* **Interactive Control Panel & Settings:** Fully interactive Main Menu state complete with functional volume sliders for music and sound effects (SFX), track tracking, and clean UI navigation.

---

## 🕹️ Controls Guide

| Key / Input | Action |
| :--- | :--- |
| **Left / Right Arrows** | Move Tetromino Left / Right |
| **Up Arrow** | Rotate Tetromino (SRS Matrix Adjusted) |
| **Down Arrow** | Soft Drop (Accelerate downward movement) |
| **Spacebar** | Hard Drop (Instant drop and lock piece) |
| **C / Left Shift** | Hold Piece Mechanic |

---

## 🛠️ Project Structure

```text
tetris/
│
├── sound_effects/            # Game soundtrack tracks and SFX assets
│   ├── soft_bg_music.wav
│   ├── midgame_bg_music.wav
│   └── hard_bg_music.wav
│
├── tetris_optimized.py       # Core application code and execution loop
└── README.md                 # Project documentation
```

---

## ⚙️ Requirements & Installation
1. Clone the repo
   ```bash
   git clone [https://github.com/YourUsername/YourRepoName.git](https://github.com/YourUsername/YourRepoName.git)
   cd YourRepoName/tetris
   ```

2. Set up a virtual environment
   ```bash
   python -m venv .venv
   # On Windows:
   .venv\Scripts\activate
   # On macOS/Linux:
   source .venv/bin/activate
   ```

3. Install Dependencies
   ```bash
   pip install pygame
   ```

4. Run the game :)

## Screenshot of the Game

<img width="796" height="793" alt="Screenshot 2026-06-01 163401" src="https://github.com/user-attachments/assets/47633a3a-6bc8-473e-94cd-529c6ccda85f" />
