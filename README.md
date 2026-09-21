# 🚗 ApexAutopilot 3.0 | Intelligent Self-Driving, Active Collision Avoidance & AI Alerts

> **Next-Generation 3D Autonomous Vehicle Platform** featuring real-time proactive collision avoidance, intelligent multi-lane gap overtaking, Forward Collision Warnings (FCW), Blind Spot Monitoring (BSM), and AI Voice Synthesizer alerts.

![ApexAutopilot Banner](https://images.unsplash.com/photo-1617788138017-80ad40651399?auto=format&fit=crop&w=1600&q=80)

---

## 🌟 What's New in 3.0

1. **🛡️ Proactive Active Collision Avoidance & Overtake (يتجنب السيارة تلقائياً)**:
   - Evaluates all 4 highway lanes in real time for clearance, vehicle velocity, and safe headway.
   - When closing in on a slower car, brake check, or road hazard, the FSD planner immediately detects adjacent open gaps and executes an autonomous, smooth evasive swerve into the clear lane.

2. **🔊 AI Voice Synthesizer & Speech Alerts (تنبيهات صوتية حية)**:
   - Integrated Web Speech API engine providing verbal automotive safety callouts:
     - *"Obstacle ahead. Swerving to Lane 2."*
     - *"Warning! Forward collision imminent. Emergency brakes applied!"*
     - *"V2X Red Traffic Light detected. Stopping."*
     - *"Pedestrian crossing ahead. Halting vehicle."*
     - *"Autonomous Autopilot Engaged."*

3. **⚠️ Forward Collision Warning (FCW) & Emergency Braking (AEB)**:
   - Real-time Time-To-Collision ($\text{TTC} = \frac{d_{lead}}{v_{rel}}$) calculation.
   - Triggers a pulsing full-screen red danger vignette, center warning banner, and piercing alarm buzzer when $\text{TTC} < 1.8\text{s}$.

4. **🟡 Blind Spot Monitoring (BSM)**:
   - Dedicated BSM indicators for left and right blind spots.
   - Prevents lane changes when an adjacent vehicle is alongside the ego vehicle.

5. **🌐 3D Ultrasonic Proximity Shield**:
   - Dynamic 3D halo ring surrounding the ego vehicle in WebGL that shifts color from Cyan (Safe) to Amber (Caution) to Neon Rose (Emergency Brake).

6. **🚦 V2X Traffic Light & God Mode Hazard Injection**:
   - Synchronized 3-color overhead traffic gantry with autonomous deceleration on Red.
   - Click anywhere on the 3D road to drop hazard cones and watch the car actively avoid them in real time!

---

## 🚀 Live Demo

Experience the live interactive simulator directly in your browser:
**[https://tareq0001.github.io/ApexAutopilot-3D-LiDAR-Vision-Simulator/](https://tareq0001.github.io/ApexAutopilot-3D-LiDAR-Vision-Simulator/)**

---

## 🎮 Controls

| Control | Action |
| :--- | :--- |
| **`Click on Road`** | Spawn Dynamic Hazard Cone to Test Auto-Evasion |
| **`VOICE ALERTS: ON/OFF`** | Toggle AI Voice Synthesizer Callouts |
| **`AUTOPILOT ON/OFF`** | Toggle Autonomous Full Self-Driving (FSD) |
| **`CLEAR NIGHT / CYBER RAIN`**| Toggle 3D Rain & Wet Asphalt Physics |
| **`AUDIO FX`** | Toggle Electric Motor Whine & Alarm Sound Effects |
| **`CHILL / STANDARD / MAD MAX`** | Select Autonomous Driving Personality Profile |

---

## 🛠️ Tech Stack

- **Graphics**: WebGL, Three.js (r128), OrbitControls
- **Mathematics & Planning**: Bézier spline trajectory ribbons, TTC calculus, Multi-lane cost-function optimization
- **Audio & Speech**: Web Speech API (`speechSynthesis`), Web Audio API (Oscillators, BiquadFilters)
- **UI & Design**: Cyberpunk dark HUD, JetBrains Mono, Outfit font, Lucide Icons

---

## 👨‍💻 Developed By

**Tareq Aboushi (أ. طارق ابوعشي)**
- GitHub: [@Tareq0001](https://github.com/Tareq0001)
- Portfolio: [https://tareq0001.github.io/](https://tareq0001.github.io/)
