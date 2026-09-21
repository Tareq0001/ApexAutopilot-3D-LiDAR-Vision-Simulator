# 🚗 ApexAutopilot 2.0 | 3D Autonomous Vehicle LiDAR, Vision & V2X Simulator

> **Next-Generation 3D Autonomous Driving Perception & Sensor Fusion Simulator** featuring real-time 64-beam LiDAR point cloud generation, Semantic Segmentation, V2X Smart Traffic Light Intersections, God-Mode Click-to-Spawn Hazards, Drive Profiles (Chill, Standard, Mad Max), and Full Mission Scenario Control.

![ApexAutopilot Banner](https://images.unsplash.com/photo-1617788138017-80ad40651399?auto=format&fit=crop&w=1600&q=80)

---

## 🌟 What's New in 2.0

1. **🚦 V2X Traffic Light & Smart Intersection Autonomy**:
   - 3D overhead gantry with synchronized 3-color traffic signals (Red, Yellow, Green).
   - Autonomous vehicle reads 5.8 GHz V2X signal: decelerates smoothly to a stop on Red behind the stop line, holds position, and accelerates on Green.

2. **🎯 God Mode: Click-to-Spawn Dynamic Hazards**:
   - Click anywhere on the 3D road to spawn immediate traffic hazards (construction cones, stalled vehicles).
   - Watch the FSD neural path planner instantly recalculate the Bézier ribbon to steer around the hazard in real time!

3. **🎨 Semantic Segmentation AI Mode**:
   - View mode classifying scene components by color masks: Drivable Road (Purple), Vehicles (Blue), Pedestrians (Orange), Infrastructure (Gray), and Sky (Void Black).

4. **⚡ Configurable FSD Drive Profiles**:
   - **CHILL**: 80 km/h cruising, conservative 2.2s headway, gentle braking.
   - **STANDARD**: 100 km/h balanced cruising, 1.6s headway, automatic overtaking.
   - **MAD MAX**: 130 km/h aggressive highway cruising, tight 1.0s headway, rapid lane changes.

5. **🌧️ Cyber Rain & Wet Surface Physics**:
   - 3D rain particle engine with wet asphalt specular reflections and reduced tire friction.

6. **🔊 Turn Signal Audio & Blind Spot Detection**:
   - Animated amber side mirror and body turn indicators.
   - Synthesized rhythmic click-clack turn signal audio via Web Audio API during autonomous lane changes.

---

## 🚀 Live Demo

Experience the live interactive simulator directly in your browser:
**[https://tareq0001.github.io/ApexAutopilot-3D-LiDAR-Vision-Simulator/](https://tareq0001.github.io/ApexAutopilot-3D-LiDAR-Vision-Simulator/)**

---

## 🎮 Controls

| Control | Action |
| :--- | :--- |
| **`Click on Road`** | Spawn Dynamic Hazard (Traffic Cone) |
| **`W` / `↑`** | Accelerate (Manual Throttle) |
| **`S` / `↓`** | Brake / Decelerate |
| **`A` / `D` or `←` / `→`** | Steer Left / Right |
| **`SPACE`** | Emergency Handbrake |
| **`AUTOPILOT ON/OFF`** | Toggle Autonomous Full Self-Driving (FSD) |
| **`CLEAR NIGHT / CYBER RAIN`**| Toggle Rain Particle Weather |
| **`AUDIO FX`** | Toggle Web Audio Synthesizer (Motor Whine, Blinkers, Chimes) |

---

## 🛠️ Tech Stack

- **Graphics**: WebGL, Three.js (r128), OrbitControls
- **Mathematics & Physics**: Keplerian & vehicle kinematics, Bézier spline polynomials, Euler integration
- **Audio**: Web Audio API (Dual-motor whine, turn signal tick, proximity beeps, FSD chimes)
- **UI & Design**: Cyberpunk dark HUD, JetBrains Mono, Outfit font, Lucide Icons

---

## 👨‍💻 Developed By

**Tareq Aboushi (أ. طارق ابوعشي)**
- GitHub: [@Tareq0001](https://github.com/Tareq0001)
- Portfolio: [https://tareq0001.github.io/](https://tareq0001.github.io/)
