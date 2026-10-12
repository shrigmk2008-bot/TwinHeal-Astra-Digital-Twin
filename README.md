# TwinHeal Astra: Digital Twin-Driven Autonomous Self-Healing Space Infrastructure

Developed for **Viksit Bharat @ 2047** | **Category:** AI and Intelligent Systems  
**Team Name:** Astra Nova  
**Members:** Shri Malathi G & Shriram Manikkam G

---

## 🛰️ Project Overview
TwinHeal Astra introduces an advanced, intelligent, and integrated **Digital Twin-driven autonomous satellite health-management framework**. Moving away from traditional reactive "Detect-Diagnose-Recover" systems, this framework implements a proactive **"Monitor-Predict-Simulate-Decide-Act-Verify"** ecosystem designed to ensure mission longevity and eliminate human intervention latencies in high-consequence space environments.

---

## 🛠️ System Architecture & Framework
The project ingests sequential time-series telemetry streams from vital physical satellite subsystems and routes them through a synchronized computing architecture:

1. **Data Ingestion Layer:** Continuous telemetry monitoring across five core subsystems:
   * **Power Systems** (Solar array outputs, battery discharge parameters)
   * **Thermal Control** (Component temperatures, radiator heat dissipation)
   * **Attitude & Orbit Control System (AOCS)** (Gyroscopes, reaction wheels telemetry)
   * **Communication Payload** (Signal gains, transmitter health)
   * **General Payload** (Mission-specific sensors)
2. **AI Prognostics Engine (LSTM):** Implements a customized **Long Short-Term Memory (LSTM) Neural Network** optimized to learn historical degradation trends and identify anomalies long before physical component failure occurs.
3. **Virtual Simulation Sandbox (Digital Twin):** Telemetry forecasts are mirrored onto a virtual 3D counterpart. The framework runs predictive "what-if" mission scenarios to evaluate structural safety constraints without risking the live spacecraft.
4. **Autonomous Control Layer:** Safely triggers predefined self-healing corrective scripts (e.g., automated workload redistribution or sub-system isolation) within safe operating bounds.

---

## 📊 Core Use Case: Solar Power Degradation
To demonstrate functionality, the current prototype mirrors a critical software simulation of solar array degradation:
* **Detection:** The predictive LSTM architecture identifies a continuous downward trend in solar output over sequential orbits (e.g., dropping from 100% to 88% efficiency).
* **Simulation:** The Digital Twin environment simulates future power margins against upcoming high-power mission phases.
* **Autonomous Action:** The autonomous decision engine stabilizes the bus voltage by executing automated load shedding of non-critical sub-systems, safeguarding primary mission operations.

---

## 💻 Tech Stack
* **AI & Machine Learning:** Python, TensorFlow / Keras, LSTM Time-Series Architecture.
* **Signal Optimization:** Kalman Filtering algorithms for telemetry noise reduction and accurate state estimation.
* **Visualization & Digital Twin Platform:** Unity 3D Engine / Unreal Engine concepts, Blender modeling software.
* **Data Transport Protocols:** Low-latency MQTT Networking Protocol and real-time WebSockets.
* **Interface & Deployment:** Figma (Interactive Dashboard Mockup), Streamlit / React.js frontend structures.

---

## 📁 Repository Contents
* `/proposals` : Contains the official 12-slide project presentation PDF.
* `/architecture-diagrams` : System block diagrams detailing telemetry synchronization loops.
* `README.md` : Project documentation, environment mapping, and functional descriptions.

---

## 🔗 Project Links
* **Interactive Figma Dashboard Mockup:**https://www.figma.com/design/f1O2hbktS2t9pRE8e1WkYT/TwinHeal-Astra-Dashboard?node-id=0-1&t=k4kFff41Nd1rtYoQ-1
* **3-Minute Project Video Presentation (YouTube):** `[Paste your YouTube unlisted video link here]`

