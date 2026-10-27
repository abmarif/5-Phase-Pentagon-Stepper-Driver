# 5-Phase-Pentagon-Stepper-Driver
Precision high-torque 5-phase pentagon stepper motor driver with smooth current chopping and microstepping logic.
# 5-Phase Pentagon Stepper Motor Driver

A custom-engineered, high-precision motion controller designed to drive 5-phase stepper motors in a pentagon configuration. Built for industrial automation, CNC machinery, and high-accuracy positioning applications requiring minimal vibration and high torque efficiency.

## 📌 Project Overview
* **Motor Topology:** 5-Phase Bipolar / Pentagon Drive Configuration
* **Core Focus:** Smooth phase-switching sequence, constant current chopping, low resonance at low speeds, and optimized thermal management.
* **Target Applications:** Precision positioning tables, CNC axes, optical positioning rigs, and textile equipment.

---

## ⚙️ Key Technical Specifications & Architecture

* **Pentagon Winding Switching:** Implemented standard 10-state / 20-state half-step and full-step switching sequences for 5-phase windings, reducing mechanical step ripple by 50% compared to standard 2-phase drivers.
* **Current Regulation:** Peak-current PWM chopping circuit ensures constant motor torque across varying RPM without exceeding coil thermal thresholds.
* **Power Stage:** Robust MOSFET H-bridge array designed with fast-recovery flyback freewheeling diodes and gate ringing suppression.
* **Protection Schemes:** Built-in overtemperature shutdown, short-circuit protection across coil phases, and under-voltage lockout (UVLO).

---

## 📁 Repository Structure

* `Hardware/` - Phase bridge schematic blocks, gate-drive topology, and PCB thermal heat dissipation notes.
* `Firmware/` - Microcontroller stepping sequence state machine, acceleration/deceleration trapezoidal profiling code snippets.
* `Media/` - Driver hardware prototype, motor hookup verification, and bench-test oscillograms.

---

## 🛠️ Tools & Technologies Used
* **EDA / Circuit Simulation:** Proteus Design Suite
* **Control / Firmware:** Microcontroller-based multi-state PWM sequencing
* **Test & Measurement:** Dual-trace Oscilloscope, Current Probe, High-power DC Supply

---

*Note: Complete schematics, detailed bridge layout gerbers, and full motor commutation firmware are proprietary assets. Contact directly for licensing or custom adaptations.*
