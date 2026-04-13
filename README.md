## Autonomous Stair-Climbing Rover — Design Modification & Virtual Testing

Design for Industry 4.0 Lab | TU Clausthal | Summer Term 2024
Master Program: Intelligent Manufacturing  
Team: Nikhil Vinayagamurthy, Davis Linston Stephen Raj, Raghav Dixit



## Project Overview

This project focused on the **"Design modification and virtual evaluation"** of an autonomous rover to enable it to climb indoor stairs up to **10 cm in height**. A base rover model was provided, and the work involved improving its stair-climbing capability through mechanical redesign, sensor integration, and physics-based simulation in **Siemens NX CAD / Mechatronics Concept Designer**.

---

##  Objectives

- Design and engineer an autonomous rover capable of climbing steps up to **10 cm**
- Ensure stable, safe, and energy-efficient autonomous navigation
- Validate the design through **virtual commissioning** and physics simulation

---

## Requirements

| Category | Requirement |
|---|---|
| Wheel modification | Ability to climb steps of 10 cm |
| Rover body | Lightweight chassis for improved mobility |
| Sensor unit | LIDAR sensor for obstacle detection |
| Power source | Increased battery capacity for continuous operation |
| Virtual testing | Physics-based simulation for stair climbing validation |

---

## Methodology

### Functional & Non-Functional Prerequisites

**Functional:**
- Height clearance of 10 cm on indoor stairs
- Stability and balance while climbing
- Obstacle detection via sensors
- Fully autonomous stair-climbing operation
- Reliable operation with built-in safety features

**Non-Functional:**
- Smooth and efficient climbing performance
- Maximized battery life
- Quiet operation with no harmful emissions
- Easy maintenance and cost-effectiveness

### Design Process

1. **Function Structure & Morphological Box** — Evaluated multiple concept solutions systematically
2. **Wheel Configuration Modification** — Adjusted wheel geometry and size to handle 10 cm steps
3. **Chassis Redesign** — Lightweight body modifications for improved mobility and stability
4. **Servo Motor Analysis** — Calculated required torque to ensure motors can overcome stair resistance
5. **CAD Modelling** — Updated full rover assembly in Siemens NX
6. **Virtual Commissioning** — Physics simulation using NX Mechatronics Concept Designer with LIDAR and compass sensors

---

## 🖥️ Simulation & Results

The virtual testing environment includes:
- Rigid body physics for rover chassis and wheels
- Collision geometry for stairs and floor
- **LIDAR sensor** for distance-based obstacle detection
- **Compass/inclination sensor** for stability monitoring
- Hinge joints for all four wheels with speed controllers

### Simulation Screenshots

| Rover Approaching Stairs | Rover Climbing with LIDAR Active |
|---|---|
| ![Rover approaching stairs](images/rover-1.jpg) | ![Rover climbing with LIDAR](images/rover-2.jpg) |

### Simulation Video

> 📹 **[Watch the full simulation video here](https://drive.google.com/file/d/16uXmguk-oOWE5EzCU11rUApPjrdHzGny/view?usp=sharing)** 

---

## Key Outcomes

- ✅ **Feasibility Proven** — Rover successfully validated for indoor stair navigation
- ✅ **Systems Integration** — Seamless integration of mechanical design, control logic, and sensor data
- ✅ **Autonomous Navigation** — Rover climbs stairs without human intervention

### Challenges & Reflections

- **Weight Optimization** — Balancing chassis weight was critical for stability and energy efficiency
- **Sensor Accuracy** — Precise LIDAR data was essential; highlighted the need for high-quality sensors
- **Iterative Design** — Each design iteration improved climbing performance significantly

---

## 🛠️ Tools & Skills

- Siemens NX (CAD + Mechatronics Concept Designer)
- Virtual commissioning & physics simulation
- Function structure & morphological box methodology
- Systems engineering & requirements analysis
- Servo motor torque calculation

---

*This project was completed as part of the Design for Industry 4.0 laboratory course at TU Clausthal.*
