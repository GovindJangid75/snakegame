# 🐍 SERPENT - Classic Snake Game Reimagined

**Developed by Govind Jangid**

A modern, visually striking, and fully responsive remake of the classic Snake game. Built with pure HTML5 Canvas, CSS3, and vanilla JavaScript—no frameworks, no external dependencies. Everything runs from a single HTML file.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## 📂 Repository Structure

```text
https://github.com/GovindJangid75/snakegame
├── index.html          # Main game file (all-in-one: HTML, CSS, JS)
└── README.md           # Project documentation
```

---

## ✨ Features

- **Fully Responsive Design**: Dynamically adjusts to any screen size—desktop, tablet, or mobile—using `ResizeObserver` and fluid CSS.
- **Canvas-Based Rendering**: Smooth 60fps gameplay with high-DPI/Retina display support.
- **Advanced Visuals**: 
  - Neon cyberpunk aesthetic with animated background blobs.
  - Snake body gradient with directional eyes.
  - Particle burst effects on food collection.
  - Screen shake and red flash on death.
  - Pulsing food with spawn animations and subtle scanline overlays.
- **Combo System**: Eat food rapidly to build a combo multiplier (up to x5) for higher scores.
- **Bonus Food**: Golden bonus orbs spawn randomly (worth 50 points) but disappear quickly!
- **Dynamic Difficulty**: Speed increases as you level up (every 60 points).
- **Sound Effects**: Synthesized audio using the Web Audio API (eat, bonus, level up, death).
- **Persistent High Score**: Saves your best score to `localStorage`.
- **Multi-Input Controls**: Keyboard (Arrows/WASD), Touch Swipe, and on-screen D-pad for mobile.

---

## 🚀 Getting Started

No installation, build steps, or servers required.

1. **Clone the repository**:
   ```bash
   git clone https://github.com/GovindJangid75/snakegame.git
   ```
2. **Open** the `index.html` file in any modern web browser (Chrome, Firefox, Safari, Edge).
3. Press **Start** or hit the **Spacebar** to play!

---

## 🎮 Controls

| Platform        | Action                  | Input                     |
|-----------------|-------------------------|---------------------------|
| 🖥️ Desktop      | Move                    | `Arrow Keys` or `W A S D` |
| 🖥️ Desktop      | Start / Pause / Resume  | `Spacebar`                |
| 📱 Mobile       | Move                    | Swipe on game board       |
| 📱 Mobile       | Move                    | On-screen D-Pad buttons   |
| 📱 / 🖥️        | UI Navigation           | Click / Tap buttons       |

---

## 🎯 Game Mechanics

- **Normal Food (Red)**: +10 points × Combo Multiplier. Grows the snake by 1 segment.
- **Bonus Food (Gold)**: +50 points. Disappears after a short time (flashes when expiring). Grows the snake by 1 segment.
- **Combo**: Eating food within a short time window increases your combo (x2, x3, x4, x5). Wait too long, and it resets.
- **Levels**: Every 60 points increases your level, which slightly increases the snake's speed.
- **Game Over**: Hitting the walls or colliding with your own body ends the game.

---

## 🛠️ Tech Stack

- **HTML5 Canvas**: For rendering the game board, snake, food, and particles.
- **CSS3**: `Flexbox`, `clamp()` for fluid typography, `backdrop-filter` for glassmorphism, `@keyframes` for animations.
- **Vanilla JavaScript (ES6+)**: 
  - `ResizeObserver` for perfect canvas scaling.
  - `Web Audio API` for programmatic sound generation.
  - `localStorage` for high score persistence.
  - `requestAnimationFrame` for the game loop.

---

## 👤 Author

**Govind Jangid**

- **GitHub**: [govindjangid75](https://github.com/GovindJangid75)
- **LinkedIn**: [govindjangid75](https://www.linkedin.com/in/govindjangid75)

---

## 📜 License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use, modify, and distribute it as you see fit.
