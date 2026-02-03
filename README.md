# 🌿 The Botanical Terrarium (v3.0)

**The Botanical Terrarium** is a high-fidelity atmospheric and botanical simulation. It features a closed-loop environment where temperature, humidity, and precipitation directly dictate the lifecycle of digital flora.

## 🚀 Live Link
**https://enonymuss-software.github.io/botanical-terrarium/**

---

## 🔬 Simulation Systems

### ☁️ Dynamic Weather Engine
The terrarium features a "Living Atmosphere" where variables interact:
* **Thermal Evaporation:** High temperatures naturally deplete humidity over time.
* **Precipitation:** Controlled rainfall restores humidity. 
* **State Changes:** When the temperature drops below **0°C**, the precipitation system switches from **Liquid Rain** to **Atmospheric Snow**, and the soil develops a **Frost Glaze**.

### 🌸 Botanical Lifecycle
Each plant is an independent object with its own DNA-driven growth path:
* **Growth Stages:** `Seed` -> `Vegetative` -> `Blooming` -> `Decay`.
* **The "Bloom" Zone:** Plants will only enter the Flowering state (Pink) when the "Goldilocks" conditions are met (20°C–28°C and 45%–65% Humidity).
* **Environmental Stress:** * 🔥 **Scorching:** Plants wither and turn brown.
    * ❄️ **Freezing:** Plants turn blue and growth stasis occurs.
    * 💀 **Mortality:** If health hits zero, the plant becomes organic matter and eventually disappears.

## 🎮 God-Mode Controls
* **🌡️ Temperature:** Slide to simulate heatwaves or arctic blizzards.
* **💧 Precipitation:** Toggle between clear skies, light rain, or heavy snow.
* **⏳ System Speed:** Accelerate time to watch generations of plants grow and die in seconds.
* **🌱 Reseed Habitat:** Inject new life into an empty or extinct ecosystem.

---

## 🛠 Technical Details
* **Graphics:** [Three.js](https://threejs.org/) WebGL Render Loop.
* **Physics:** Particle-based weather system with sway-interpolation for snow.
* **Architecture:** Stateless, client-side execution (No server required).

## ⚖️ License
This project is protected under the **MIT License**.

---
*Observe the delicate balance of life and atmosphere.*
