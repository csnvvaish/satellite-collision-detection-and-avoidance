
# 🚀 Satellite Collision Detection and Avoidance System
## 🛰️ Overview
An interactive real-time simulation system that models satellite motion in Low Earth Orbit (LEO), detects potential collisions, and autonomously triggers avoidance maneuvers. Built using CesiumJS, the system visualizes space traffic and demonstrates decision-making under critical conditions.
---
## ⚡ Key Features
- 🌍 Real-time 3D orbital simulation using CesiumJS  
- 📏 Continuous distance monitoring between space objects  
- 🚨 Collision detection using proximity thresholding  
- 📊 Dynamic threat level classification (Low / Medium / High)  
- 🛡️ Autonomous collision avoidance via orbit adjustment  
- ☄️ Space debris simulation and impact detection  
- 🎛️ Interactive control panel (Start, Pause, Speed, Reset)  
- 📡 Live mission monitoring dashboard  
---
## 🧠 System Logic
- Satellites follow mathematically modeled orbital paths  
- Distance between objects is calculated continuously  
- When objects enter a critical range:
  - System raises a collision alert  
  - Threat level escalates  
  - Autonomous avoidance is triggered  
  - Satellite orbit is modified to prevent impact  
---
## 🛠️ Tech Stack
- **JavaScript**  
- **CesiumJS** (3D Geospatial Visualization Engine)  
- **HTML5 & CSS3**  
---
## ▶️ Getting Started
### 1. Clone the repository
```bash
git clone https://github.com/csnvvaish/satellite-collision-detection-and-avoidance.git
