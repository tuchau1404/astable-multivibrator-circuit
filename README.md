# Astable Multivibrator Design and Simulation

## Overview
This project focuses on the design, simulation, and analysis of an **astable multivibrator** using LTSpice XVII. The circuit generates a continuous square wave without an external trigger and is commonly used for clock signal generation, LED blinking, and timing applications.

The work was completed as part of the **Engineering Design (61ECE114)** module at **Vietnamese-German University (VGU)** during the Winter Semester 2023/24.

---

## Objectives
- Create an LTSpice schematic of the given astable multivibrator circuit.
- Perform transient simulations to analyze waveform characteristics.
- Measure and evaluate:
  - Output amplitude
  - Frequency of oscillation
  - Duty cycle
  - Rise and fall times
- Investigate the impact of varying resistor and capacitor values.
- Optimize component selection to meet specific design requirements:
  - Frequency: **2.0 Hz ±10%**
  - Duty cycle: **20–25%**
  - Rise time: **< 10 ms**

---

## Circuit Description
The circuit uses:
- **BC547B** NPN transistors
- **Resistors (E12 series)**
- **Capacitors** for timing control
- **LEDs** as visual indicators of oscillation

Operation is based on capacitor charging/discharging through resistors, creating continuous switching between two quasi-stable states.

---

## Key Results
- **Initial Design:** Verified oscillation and measured baseline frequency, duty cycle, and amplitude.
- **Component Variation:** Tested multiple R and C configurations to observe frequency and duty cycle changes.
- **Final Design:** Achieved 2.0 Hz oscillation with 22% duty cycle and rise time under 10 ms.

---

## Tools Used
- **LTSpice XVII** – Circuit design and simulation
- `.MEASURE` directive – Automated measurement of waveform parameters

---

## How to Reproduce
1. Open the provided LTSpice `.asc` file.
2. Run transient simulation for at least **3 seconds**.
3. Use `.MEASURE` commands to calculate:
   - Frequency
   - Duty cycle
   - Rise/Fall times
4. Adjust resistor and capacitor values as needed to match design requirements.

---

## Applications
- LED blinking circuits
- Clock signal generation
- Pulse-width modulation (PWM) training circuits
- Basic oscillator for educational purposes

---

## Author
**[Your Name]**  
Vietnamese-German University (VGU)  
Winter Semester 2023/24 – Engineering Design

---
