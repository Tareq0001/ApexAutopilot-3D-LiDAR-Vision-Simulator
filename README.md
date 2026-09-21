# 🚗 ApexAutopilot | 3D Autonomous Vehicle LiDAR & Vision Perception Simulator

> **Next-Generation 3D Autonomous Driving Perception & Sensor Fusion Simulator** featuring real-time 64-beam LiDAR point cloud generation, Extended Kalman Filter (EKF) tracking, 3D bounding box detection, adaptive trajectory planning, and full mission scenario control.

![ApexAutopilot Banner](https://images.unsplash.com/photo-1617788138017-80ad40651399?auto=format&fit=crop&w=1600&q=80)

---

## 🌟 Highlights & Key Features

- **64-Beam LiDAR Point Cloud Engine**:
  - Real-time 360° raycasting with 16,000+ points color-coded by elevation (Z-axis) and intensity.
  - Multi-beam scan simulation reproducing Velodyne / Luminar LiDAR sensor physics.
- **AI Perception & 3D Bounding Box Tracking**:
  - 3D bounding boxes around surrounding traffic (Cars, Trucks, Vans) and pedestrians with real-time classification & confidence scores.
- **Autonomous Trajectory Planner (Bézier Ribbon)**:
  - Real-time cubic spline polynomial trajectory ribbon projecting the vehicle's planned path.
  - Adaptive Cruise Control (ACC), automatic lane changing for overtaking slower traffic, and Emergency Braking (AEB).
- **Multiple Sensor & Camera Modes**:
  - **Chase View**: Cinematic third-person vehicle following camera.
  - **LiDAR Only Mode**: Pitch-black developer view isolating pure point cloud and 3D wireframe bounding boxes.
  - **Bird's Eye View (BEV)**: Top-down sensor occupancy grid.
  - **Cockpit / Windshield View**: Real-time driver perception view.
- **Interactive Scenarios**:
  - `Highway Cruise & Overtake`: High-speed 110 km/h highway navigation with automatic lane changes.
  - `Urban Crosswalk & Yield`: City street navigation with crossing pedestrians and yield logic.
  - `Sudden Cut-In & AEB`: Sudden rogue vehicle lane cut-in triggering emergency braking.
  - `Dense Fog & Sensor Degradation`: Simulated zero-visibility fog testing sensor fusion resiliency.
- **Synthesized Web Audio Engine**:
  - Electric dual-motor whine modulated by speed and throttle.
  - Ultrasonic proximity alert chimes.
  - Tesla-style two-tone Autopilot engage/disengage sound effects.
- **Zero Dependencies**: Pure HTML5, WebGL, Three.js, and Web Audio API.

---

## 🚀 Live Demo

Experience the live interactive simulator directly in your browser:
**[https://tareq0001.github.io/ApexAutopilot-3D-LiDAR-Vision-Simulator/](https://tareq0001.github.io/ApexAutopilot-3D-LiDAR-Vision-Simulator/)**

---

## 🎮 Controls

| Control | Action |
| :--- | :--- |
| **`W` / `↑`** | Accelerate (Throttle) |
| **`S` / `↓`** | Brake / Decelerate |
| **`A` / `D` or `←` / `→`** | Steer Left / Right |
| **`SPACE`** | Emergency Handbrake |
| **`AUTOPILOT ON/OFF`** | Toggle Autonomous Full Self-Driving (FSD) |
| **`AUDIO FX`** | Toggle Web Audio Synthesizer |

---

## 🛠️ Tech Stack

- **Graphics**: WebGL, Three.js (r128), OrbitControls
- **Mathematics & Physics**: Keplerian & vehicle kinematics, Bézier spline polynomials, Euler integration
- **Audio**: Web Audio API (Oscillators, BiquadFilters, GainNodes)
- **UI & Design**: Cyberpunk dark HUD, JetBrains Mono, Outfit font, Lucide Icons

---

## 👨‍💻 Developed By

**Tareq Aboushi (أ. طارق ابوعشي)**
- GitHub: [@Tareq0001](https://github.com/Tareq0001)
- Portfolio: [https://tareq0001.github.io/](https://tareq0001.github.io/)
