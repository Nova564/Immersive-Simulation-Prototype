# TER Train Simulator - VR Guidance Prototype
> **Technical Challenge - SNCF(May 2026)**

A functional Unreal Engine prototype simulating the realistic kinematic behavior of a train on tracks, optimized for Virtual Reality (VR) performance.

---

## 🛠️ Core Features

* **Dual-Bogie Guidance:** Dynamically calculates front and rear axle positions using a 150 cm `BogieOffset` and `Find Look At Rotation` to ensure perfect alignment in curves without derailment.
* **"Set Speed" System:** Simulates real-world SNCF train controls (`Target Speed` interpolation) instead of arcade car acceleration, including a cruise control feature.
* **Dynamic Switch & Route Bis:** Features a smooth track bifurcation secured by distance-gated checks to prevent physics glitches, paired with a responsive physical switch lever.
* **Optimized HUD & Dual Camera:** Displays a clean, lag-free UI and supports instant toggling between a Spectator Free Cam and a 3rd Person Train Cam.


---

## ⌨️ Controls
* **Z** Accelerate (Increase Target Speed)
* **S / Down Arrow:** Brake (Decrease Target Speed)
* **U:** Cruise Control (Lock speed)
* **E:** Toggle Switch Route (Main / Bis)
* **C:** Toggle Camera View (Free Cam <-> 3rd Person Cam)
