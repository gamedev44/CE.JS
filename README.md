````markdown
# Cymatics Engine 3D (CE.js)

[![Three.js](https://img.shields.io/badge/three.js-v0.152.2-blue)](https://threejs.org/) [![License: IWI‐PCL](https://img.shields.io/badge/License-IWI--PCL-red)](#license)

> Real-time 3D particle & wave‐shaping engine built on Three.js

---

## 📋 Table of Contents

1. [Features](#features)  
2. [Demo & Installation](#demo--installation)  
3. [Controls](#controls)  
4. [Presets & Camera](#presets--camera)  
5. [License](#license)  
6. [Credits](#credits)  

---

## 🌟 Features

- **Real-time 3D Particles**  
  Render tens of thousands of particles at 60 FPS.

- **Multi-Axis Wave Shaping**  
  XY & Z-axis frequency modulation for intricate structures.

- **Advanced Physics**  
  - Center-point gravity  
  - Rotational vortex  
  - Global damping

- **Inter-Particle Forces**  
  - Repulsion & cohesion  
  - Clustered vs. fluid behaviors

- **Waveform Selection**  
  Instant switch between Sine, Square, Triangle, Sawtooth.

- **Built-in Presets**  
  From atomic orbitals → galactic spirals.

- **Full Camera Control**  
  Orbit, pan, zoom from any angle.

---

## 🚀 Demo & Installation

- **Live Demo:**  
  Open in your browser — no build required.  
  <https://your-live-demo-url.com>

- **Local Mode (Offline/GPU-accelerated):**  
  1. Download the ZIP from GitHub.  
  2. Unzip and open `index.html` in Chrome/Firefox.  
  3. Enjoy full GPU/CPU utilization without lag.

---

## 🕹️ Controls

### Camera

| Action  | Input                   |
| ------- | ------------------------|
| Rotate  | Left-click + drag       |
| Pan     | Right-click + drag      |
| Zoom    | Mouse wheel             |

### Pattern Parameters

- **Frequency**  
  - XY Frequency slider  
  - Z Frequency slider

- **Physics**  
  - Amplitude  
  - Gravity  
  - Damping  

- **Interaction**  
  - Repulsion  
  - Cohesion  

### Preset Export

1. Position camera  
2. Click **Get Camera State**  
3. Copy `camPos` & `camZoom` into your preset JSON

---

## 🔧 Presets & Camera

Presets live in `/src/presets/`. Each entry:

```jsonc
{
  "name": "Galactic Spiral",
  "waveform": "sine",
  "freq": { "x": 4, "y": 3, "z": 1 },
  "forces": { "gravity": 0.2, "vortex": 0.1, "damping": 0.05 },
  "interaction": { "repel": 0.8, "cohere": 0.3 },
  "camera": { "position": [1.2, 0.8, 2.5], "zoom": 1.4 }
}
````

---

## ⚖️ License

This project is proprietary under the **IronWill Interactive Proprietary Contributor License (IWI-PCL)**.
Unauthorized use, distribution, or modification is prohibited.

---

## 👥 Credits

* **Joshua Herrell** — Founder & CEO, IronWill Interactive Entertainment

> Built with passion at IronWill Interactive Entertainment.

```
```
