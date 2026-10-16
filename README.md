<h1 align="center">José Luis Segundo Manayay</h1>

<p align="center">
  <b>Robotics & AI Engineer</b> · Control Systems · Software Engineering · Embedded Systems<br>
  Mechatronics Engineering — Universidad Nacional de Ingeniería (UNI), Lima, Peru
</p>

<p align="center">
  <a href="https://linkedin.com/in/josesegundom">LinkedIn</a> ·
  <a href="https://orcid.org/0009-0002-9203-8710">ORCID</a> ·
  <a href="https://www.scopus.com/authid/detail.uri?authorId=60590456800">Scopus</a> ·
  <a href="mailto:josesegundomanayay0604@gmail.com">Email</a>
</p>

---

I build autonomous systems end to end — dynamic model, controller, perception and the software
that ties them together — and validate them in simulation before they reach hardware. My research
combines **nonlinear and predictive control** (NMPC, adaptive backstepping, sliding mode) with
**reinforcement learning** for UAVs, legged robots and space robotics.

- 🤖 Deputy Director of Control Systems — CEDIM (Mechatronics R&D Center, UNI)
- 🛰️ Aerospace & Autonomous Systems Researcher — CAMI (UNI)
- 📄 5 Scopus-indexed conference papers (LACCEI, IAC) · 3 more presented at IAC 2026

**Stack:** Python · C/C++ · TypeScript · Julia · MATLAB — ROS 2 · Gazebo · MuJoCo · PX4 · acados/CasADi · ONNX Runtime — React · Supabase · Docker · GitHub Actions — ESP32 · FreeRTOS

---

## 🤖 Robotics & Autonomous Systems

| Project | Highlights | |
|---|---|---|
| [**hrfest2026_lidar_dock_cedim**](https://github.com/JoseSegundoM/hrfest2026_lidar_dock_cedim) | LiDAR-only docking of an iRobot Create 3: RANSAC/TLS wall fitting, marker detection, dock as a Kalman landmark in `odom`, two-stage controller. 8/8 Gazebo runs, 72/72 closed-loop bench runs. | ROS 2 · HRFEST 2026 |
| **NMPC + DRL residual control for UAVs** — *Bachelor's thesis* | acados NMPC (C++, 100 Hz) + PPO residual on the reference for quadrotors in confined mine galleries; 29–42 % RMSE reduction vs. pure NMPC under disturbances (simulation, n = 8 seeds); 1.2 ms mean cycle latency. | 🔒 code on request |
| **RL informative path planning for UAVs** — *Professional-degree thesis (in progress)* | Deep-RL adaptive informative path planning for early late-blight detection in potato crops; PX4 + ROS 2, Docker, CI. | 🔒 in progress |
| **MineSentinel** — underground inspection quadruped | ROS 2 autonomy stack, LiDAR-inertial SLAM (FAST-LIO2, Livox Mid-360) and RGB-D perception on a DOBOT X1 platform, NVIDIA Jetson. [LACCEI 2026 paper](https://doi.org/10.18687/LACCEI2026.1.1.2664) | 🔒 team project |
| **Planetary & orbital robotics** | Adaptive backstepping for coaxial drones in Martian lava tubes; backstepping impedance control for capturing tumbling space debris (IAC 2026). | 🔒 publication pending |

## 🎛️ Control Systems & Simulation

| Project | Highlights | |
|---|---|---|
| **Cubli momentum-budget benchmark** | LQR vs. feedback linearisation vs. sliding mode vs. backstepping on a reaction-wheel inverted pendulum, with momentum-saturation-aware evaluation. | 🔒 release planned |
| **CubeSat ADCS** | Feedback linearisation + LQR attitude control for a 2U CubeSat. [IAC 2025 paper](https://doi.org/10.52202/083087-0138) | paper |

## 🧠 Software Engineering & AI

| Project | Highlights | |
|---|---|---|
| **Smart SSOMA** | Machine-vision PPE-compliance monitoring on edge devices for industrial and construction safety. [LACCEI 2026 paper](https://doi.org/10.18687/LACCEI2026.1.1.2671) | paper |
| **Production e-commerce platform** (client) | React 19 + TypeScript + Supabase (RLS, Edge Functions) + Netlify, Playwright end-to-end tests. | 🔒 client work |
| **AI automation** | RAG assistants and LLM agents for business workflows (freelance and AI Engineering internship). | 🔒 client work |

## 🔌 Electronics & Embedded Systems

| Project | Highlights | |
|---|---|---|
| **KonSat-1** | Multisensor CubeSat payload (optical + AIS) for detecting ship oil pollution. [IAC 2025 paper](https://doi.org/10.52202/083084-0035) | paper |
| **Modular educational CubeSat** | Modular CubeSat platform for aerospace engineering education in Peru. [IAC 2025 paper](https://doi.org/10.52202/083097-0138) | paper |

---

## 📄 Publications

**Scopus-indexed**

1. **J. L. Segundo Manayay**, J. Y. Garay Yovera, R. G. Chávez Chávez, F. Rodríguez Huiman, F. A. Castro Suazo, R. N. Antayhua Alvarez, J. A. Espinoza Coronel. *A Multimodal 3D Perception-Based Autonomous Robotic Architecture for Underground Mining: Predictive Planning and Dynamic Risk-Aware Control.* LACCEI 2026. [DOI](https://doi.org/10.18687/LACCEI2026.1.1.2664) · [Scopus](https://www.scopus.com/record/display.uri?eid=2-s2.0-105048843694&origin=resultslist)
2. **J. Segundo**, J. Garay, R. Chávez, F. Rodríguez, F. Castro, R. Antayhua, J. Espinoza. *Smart SSOMA: Design and Implementation of an Adaptable, Comprehensive SSOMA Safety Management System to Reduce Reporting Times for PPE Non-Compliance, Using Machine Vision and Edge Computing, Applied to Industrial and Construction Environments.* LACCEI 2026. [DOI](https://doi.org/10.18687/LACCEI2026.1.1.2671) · [Scopus](https://www.scopus.com/record/display.uri?eid=2-s2.0-105048862996&origin=resultslist)
3. **J. L. Segundo Manayay** et al. *KonSat-1: Multisensor System for Detecting Oil Pollution from Ships Using Optical and AIS Technologies.* IAC 2025. [DOI](https://doi.org/10.52202/083084-0035) · [Scopus](https://www.scopus.com/record/display.uri?eid=2-s2.0-105040618203&origin=resultslist)
4. R. Chávez, …, **J. Segundo**, G. Joo. *Nonlinear Control with Feedback Linearization for ADCS in 2U CubeSat: LQR-Based Control Strategy.* IAC 2025. [DOI](https://doi.org/10.52202/083087-0138) · [Scopus](https://www.scopus.com/record/display.uri?eid=2-s2.0-105036334623&origin=resultslist)
5. J. S. Palacios Bett, …, **J. L. Segundo Manayay**, … *Design of a Modular Educational CubeSat as a Tool for Aerospace Engineering Education in Peru.* IAC 2025. [DOI](https://doi.org/10.52202/083097-0138) · [Scopus](https://www.scopus.com/record/display.uri?eid=2-s2.0-105036339461&origin=resultslist)

**Presented at IAC 2026 (Antalya) — publication pending**

- Adaptive backstepping control for coaxial drones in Martian lava tubes (paper 116992)
- Adaptive backstepping impedance control for robotic capture of tumbling space debris (paper 116744)
- Simulation-based circular-economy framework for Artemis-era lunar habitats (paper 118092)

**Awards** — 2nd place, Scientific Payload, ISSSP 2025 (team *Supertronics*) · LACCEI Student Paper Finalist 2026

---

<sub>🔒 Research code is kept private until publication and co-author approval. Reviewers, admissions committees and recruiters can request access.</sub>
