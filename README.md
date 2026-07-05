
# 🌆 Commit City

> Turn your GitHub contribution history into a living cyberpunk skyline.

Commit City transforms GitHub activity into an interactive 3D city where every day becomes a building, every commit shapes the skyline, and coding streaks light up the metropolis with neon energy.

Built with Three.js and inspired by retro-futuristic cyberpunk aesthetics, Commit City visualizes an entire year of contributions as an explorable cityscape directly in the browser.

docs/banner.png

---

## ✨ Features

### 🏙 3D GitHub City Visualization
- Every day becomes a building.
- Taller buildings represent more commits.
- Empty days become vacant lots.
- Streaks create brighter neon districts.

### 🌈 Language-Based Districts
Buildings are color-coded using repository language data:

| Language | Color |
|-----------|---------|
| JavaScript | Blue |
| TypeScript | Light Blue |
| Python | Neon Green |
| HTML | Orange |
| CSS | Purple |
| Java | Amber |
| Go | Cyan |
| Rust | Orange |
| Shell | Lime |
| Other | Slate |

### 🎮 Interactive Navigation
- Drag to orbit the city
- Scroll to zoom
- Hover buildings for details
- Auto-cinematic camera movement

### 🌧 Cyberpunk Atmosphere
- Animated neon lighting
- Flying traffic
- Rain effects
- Reflections
- Scanlines and CRT-style HUD

### 📊 Live GitHub Integration
- Pulls public contribution history
- Uses repository language information
- No authentication required
- No data stored

### 📁 Custom Data Import
Import your own dataset with:

```json
[
  {
    "date": "2026-01-15",
    "count": 4,
    "lang": "Python"
  }
]
