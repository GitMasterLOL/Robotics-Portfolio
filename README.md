# Robotics-Portfolio

This repository indexes my major hands-on engineering projects in robotics, embedded systems, PCB design, and mechanical CAD.

---
## 1. Offroad UGV mechanical design (Internship)
🔗 Repo: [link](https://github.com/GitMasterLOL/offroad-ugv-mechanical-design.git)

**Project Overview:**
Offroad capable Umanned Ground Vehicle built for last mile military deliveries and logistics

**My contributions:**
- Designed and manufactured a complete 100 kg-payload off-road UGV from scratch, replacing a scrapped prototype
with a 60 kg aluminium T-slot and sheet metal chassis rated for a 1.3 kW peak drivetrain load, developed as a
quieter, lower-cost alternative to trucks for army border logistics
- Engineered a mild steel trailing arm suspension and chain drive transmission with custom motor and sprocket
mounts, validating arm deformation under full payload through FEA in Ansys and iterating geometry in Onshape
before fabrication
- Led fabrication and assembly of all mechanical subsystems alongside supporting power and electronics integration,
delivering the rover for public demonstration at the National Defence Conclave (T-Works, Hyderabad) to positive
stakeholder response

**Key skills demonstrated:**
Parametric CAD, Structural analysis, Design for Manufacturing and Assembly

---
## 2. Vyadh Robotic Arm (Team Project)
🔗 Repo: [link](https://github.com/RobArmGit/RobArm)

**My role & contributions:**
- Led the development of a 6-DOF remotely controlled robotic arm with 10kg payload for an international Mars rover
competition, implementing a modular control architecture using ESP32 modules with bluetooth communication for
hardware interfacing, achieving sub-1° positional precision across the full workspace of 1m radius
- Architected a fully custom ROS2 message interface layer from scratch, enforcing a unified communication standard
using custom interface types across all arm subsystems to improve code readability and cross-team development
consistency
- Integrated encoder feedback and motor drivers with custom 3D-printed mounts designed for reliability and rapid field
swap-out, cutting assembly time and improving thermal reliability under competition conditions
- Guided and mentored a domain of 5 juniors across electronics and software subteams, defining component selection
criteria and integration standards that improved system modularity and eliminated cross-subsystem conflicts during
final assembly

**Key skills demonstrated:**
Mechatronics integration, CAD, PCB design, embedded systems, control systems

---
## 3. Portable Oscilloscope PCB
🔗 Repo: [PocketScope](https://github.com/GitMasterLOL/PocketScope)

**Project overview:**
Design of a compact, low-cost oscilloscope intended for learning mixed-signal circuit design, signal conditioning, and noise management in embedded measurement systems.

**My contributions:**
- Designed multiple PCB revisions focusing on analog front-end layout, power integrity, and ADC signal routing
- Implemented input scaling to measure higher-voltage signals using low-voltage microcontroller ADCs
- Iterated on board layout to reduce noise, ground bounce, and coupling between digital and analog sections

**Key skills demonstrated:**
PCB design, mixed-signal electronics, schematic capture, hardware debugging mindset

**Pending work:**
Housing design, Communication system, GUI design for signal visualization

---
## 4. Motor Driver Enclosure with Active Cooling
🔗 Repo: [Motor Driver Enclosure](https://github.com/GitMasterLOL/Motor-Driver-enclosure)

**Project overview:**
Mechanical design of a compact motor driver enclosure incorporating magnetic holders and forced-air cooling to improve thermal performance and reliability in high-current unstable operation.

**My contributions:**
- Designed a 3D CAD enclosure optimized for stability, airflow, component accessibility, and mounting constraints
- Integrated a fan-based cooling path
- Considered manufacturability, cable routing, and maintenance access in the
  mechanical layout

**Key skills demonstrated:**
Mechanical CAD, enclosure design, thermal considerations, practical manufacturability
