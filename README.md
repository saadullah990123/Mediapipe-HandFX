# ✋ Mediapipe-HandFX

> **Turn your hand movements into real-time interactive canvas magic.**

An interactive web app that maps 21 3D hand-tracking landmarks to visual canvas effects directly inside your browser using **MediaPipe JS** and **HTML5 Canvas**.

<div align="center">

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=for-the-badge&logo=google&logoColor=white)](https://developers.google.com/mediapipe)
[![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com/)

[![GitHub Stars](https://img.shields.io/github/stars/saadullah990123/Mediapipe-HandFX?style=flat-square&color=blue)](https://github.com/saadullah990123/Mediapipe-HandFX/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/saadullah990123/Mediapipe-HandFX?style=flat-square&color=blue)](https://github.com/saadullah990123/Mediapipe-HandFX/network/members)
[![GitHub Issues](https://img.shields.io/github/issues/saadullah990123/Mediapipe-HandFX?style=flat-square&color=blue)](https://github.com/saadullah990123/Mediapipe-HandFX/issues)
[![License](https://img.shields.io/github/license/saadullah990123/Mediapipe-HandFX?style=flat-square&color=blue)](LICENSE)

</div>

---

## 📖 Overview

**Mediapipe-HandFX** tracks 21 3D hand landmarks in real time through your webcam feed and maps them directly onto an HTML5 `<canvas>` layer. Built entirely with vanilla **HTML5, CSS3, and JavaScript**, it executes locally via WebAssembly without requiring backend compilation or game engines.

---

## ✨ Key Features

| Feature | Description |
| :--- | :--- |
| 🖐️ **Landmark Tracking** | Detects 21 3D landmarks per hand at native frame rates |
| 🎆 **Dynamic FX Engine** | Render fingertip particle trails, glows, and motion graphics |
| 🎯 **Gesture Detection** | Trigger specific visual effects based on hand poses |
| ⚡ **Client-Side WASM** | Runs locally in-browser via WebAssembly |
| 📱 **Cross-Platform** | Fully responsive layout for desktop and mobile browsers |

---

## 🛠️ Built With

* **HTML5** — Document structure, `<video>` webcam stream, and `<canvas>` layer
* **CSS3** — Custom glassmorphism UI overlays and responsive layout
* **JavaScript (ES6+)** — Application state, rendering loops, and modular effect handlers
* **[MediaPipe Hands JS](https://developers.google.com/mediapipe/solutions/vision/hand_landmarker/web_js)** — Computer vision pipeline for landmark detection

---

## 📂 Project Structure

```text
Mediapipe-HandFX/
├── index.html            # Main entry document (video & canvas layers)
├── css/
│   └── style.css         # Styling for UI overlays and responsive viewport
├── js/
│   ├── app.js            # Engine initialization and animation loop
│   ├── handTracking.js   # MediaPipe Hands JS wrapper
│   ├── effects/
│   │   ├── trailEffect.js # Particle trail generation logic
│   │   └── glowEffect.js  # Fingertip glow rendering logic
│   └── utils/
│       └── helpers.js    # Geometric vector calculations
└── README.md             # Project documentation

📄 License
Distributed under the MIT License. See LICENSE for details.

Made with ❤️ by Saadullah
