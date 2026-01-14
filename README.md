#  Space Explorer Rover – Thermal Monitoring & Control Dashboard

An interactive **frontend simulation dashboard** designed to monitor and control the thermal state of a space exploration rover.  
The system demonstrates **autonomous decision-making** based on temperature thresholds along with a **human override mode**, similar to real-world mission control systems.

---

## Live Demo

🔗 https://chinmay-kumbar.github.io/Space-Rover/

*(Open the link to interact with the simulation in real time)*

---

## Project Overview

This project visualizes rover telemetry data and simulates how a rover reacts to changing thermal conditions.  
It operates in **automatic mode by default**, where the system independently manages cooling and thermal protection.  
A **human override mode** allows manual intervention, simulating real mission-control scenarios.

---

## Key Features

-  **Real-time Temperature Simulation**  
  Simulate rover surface temperature using an interactive slider.

-  **Autonomous Thermal Control (Automatic Mode)**  
  - Activates cooling when temperature exceeds safe limits  
  - Deploys thermal shield during critical overheating  
  - Switches rover state between *Stable*, *Warning*, and *Critical*

-  **Human Override Mode**  
  - Manually control cooling system and thermal shield  
  - Overrides automatic system decisions  
  - Clearly indicated in UI and system logs

-  **System Status & Alerts**  
  - Dynamic status badges and alert messages  
  - Color-coded system states

-  **Live Telemetry & Activity Log**  
  - Timestamped system events  
  - Logs both automatic and manual actions

-  **Responsive UI**  
  - Space-themed dark UI  
  - Works across desktop and mobile screens

---

## 🛠️ Tech Stack

- **HTML5** – Structure  
- **CSS3** – Styling, layout, and theming  
- **JavaScript (Vanilla)** – Simulation logic, state management, and interactivity  
- **GitHub Pages** – Deployment

---

## ⚙️ System Logic (Simplified)

| Temperature Range | System Behavior |
|------------------|-----------------|
| ≤ 35°C | Normal operation |
| 36°C – 50°C | Cooling system auto-activated |
| > 50°C | Thermal shield deployed & safe mode triggered |

In **Human Override Mode**, all actuator controls are handled manually.

---

## ▶️ How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/Chinmay-Kumbar/Space-Rover.git
