# 🌌 Quantum Jump // Neo-Arcade Experience

[![Engine](https://img.shields.io/badge/Engine-Vanilla%20JS-00f2fe?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Graphics](https://img.shields.io/badge/Graphics-HTML5%20Canvas-7000ff?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![Audio](https://img.shields.io/badge/Audio-Web%20Audio%20API-ffff00?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
[![Design](https://img.shields.io/badge/Design-Glassmorphism-ff007f?style=for-the-badge)](https://css-tricks.com/glassmorphism-css-monitor/)

A premium, high-fidelity neon arcade micro-game built entirely with raw vanilla web standards. Blending sleek, minimalist aesthetics inspired by high-end motion design studios with retro arcade muscle-memory loops, **Quantum Jump** challenges players to navigate a fluid, procedurally generated obstacle course within a strictly single-viewport interactive environment.

---

## 🕹️ Gameplay Mechanics

Quantum Jump features a responsive, multi-tier movement toolkit that forces fast decision-making and rhythmic flow:

*   **Jump:** Tap `SPACEBAR` or click/tap the canvas to execute a standard physics-weighted airborne arc.
*   **Double Leap:** Tap `SPACEBAR` while mid-air to trigger a secondary atmospheric burst, complete with unique visual particles.
*   **Dodge Slide:** Hold `↓ ARROW` or `S` to instantly squash your player vector down by **50%**, flattening into an ellipse to slide safely under low-flying threats.

---

## 🚀 Core Features

### ⚡ Pure Canvas Vector Physics
The runtime calculates precise circular-to-box and capsule shape intersections entirely within a native HTML5 `CanvasRenderingContext2D` framework. It features real-time gravity scaling, momentum accumulation, and custom directional explosion particles.

### 🧠 Smart Pattern Sequencing
Replaces erratic random generation with an intentional level generator. The engine cues up curated obstacle matrices—such as single tall spikes, specialized low drones, and rapid **jump-then-duck combinations**—to favor muscle-memory mastery over unfair chaos.

### 🎹 Live Hardware Audio Synthesis
Operates with a **strict zero-asset footprint**. Instead of downloading bulk `.mp3` or `.wav` files, the game connects directly to the browser's hardware soundcard via the **Web Audio API**, synthesizing customized 8-bit retro wave chirps, blips, and noise explosions on the fly using code-based oscillators and gain nodes.

### 🎨 Chromatic Feedback Loop
As your score progresses, a dynamic HSL tracking system smoothly sweeps the global background hues through a shifting color spectrum, continuously modifying ambient gradients and player accents to visually signal scaling game velocity.

### 💎 Premium Luxury Interface
Inspired by award-winning digital experiences, the single-viewport design is locked seamlessly to `100vh` to prevent messy scroll behavior. It incorporates a mouse-tracking mesh aura, parallax background decoration layers, interactive 3D card tilt transformations, and crisp typography.

---

## 🛠️ Architecture & Tech Stack

This project was built strictly without external frameworks, preprocessors, or asset dependencies to demonstrate the raw power of modern web standards:

*   **Markup:** Semantic HTML5 Structure
*   **Styling:** Modern CSS3 (Custom Grid Matrix, CSS Variables, Flexbox, Fluid Typography)
*   **Logic Engine:** Vanilla ECMAScript 6+ Core (`requestAnimationFrame` loops)
*   **Graphics:** HTML5 Canvas API Vector Mapping
*   **Audio Engine:** Web Audio API Frequency Controllers

---

## 💾 Installation & Local Execution

Because the repository relies completely on native client-side web technologies, there is no need for local servers, node module extractions, or environment installations.

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/EncryptWiser/quantum-jump.git](https://github.com/EncryptWiser/quantum-jump.git)
