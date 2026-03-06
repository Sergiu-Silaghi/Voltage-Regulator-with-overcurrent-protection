# Voltage-Regulator-with-Overcurrent-Protection
Voltage regulator with overcurrent protection designed and simulated in OrCAD, ensuring an output voltage within a specified range and a current limitation.

## Overview
This project presents the design and simulation of a **voltage regulator with overcurrent protection**, developed using **OrCAD**. The objective of the circuit is to provide a **stable DC output voltage within a specified operating range** while ensuring safe operation through a current limiting protection mechanism.

The regulator is designed so that the **output voltage remains within the range of 6 V to 19 V**, even under varying load conditions, while the protection circuit prevents excessive current from flowing through the system.

The project includes the **complete schematic design and circuit simulation** performed in the OrCAD environment.

## Design Specifications

- **Minimum output voltage:** 6 V  
- **Maximum output voltage:** 19 V  
- **Maximum output current:** 1 A  
- **Protection mechanism:** Overcurrent protection (current limiting)  
- **Design and simulation environment:** OrCAD / PSpice

---

## System Description

The circuit is designed to ensure reliable voltage regulation while protecting the system against overload conditions. The architecture consists of two main functional blocks:

1. **Voltage Regulation Stage**
2. **Overcurrent Protection Circuit**

These blocks work together to maintain stable operation and protect both the regulator and the connected load.

---

## Voltage Regulation Stage

The voltage regulation stage is responsible for maintaining a **stable DC output voltage within the specified operating range**.

The design ensures that: 6 V ≤ Vout ≤ 19 V

This is achieved through a regulation mechanism based on feedback control, which stabilizes the output voltage despite variations in load current or input conditions.

---

## Overcurrent Protection

To ensure safe operation, the circuit integrates a **current limiting protection mechanism** that prevents the output current from exceeding a predefined limit.

Key characteristics:

- **Current limit:** 1 A
- Protection against overload conditions
- Prevention of excessive power dissipation
- Protection of both the regulator circuitry and the load

When the load current approaches the maximum allowable value, the protection circuit activates and limits the current, preventing potential damage to the system components.

---

## Simulation and Verification

The circuit was designed and analyzed using **OrCAD Capture and PSpice simulation tools**. Simulations were performed to evaluate:

- Output voltage behavior within the specified range
- Circuit response under different load conditions
- Activation of the overcurrent protection mechanism

The simulation results confirm that the circuit maintains the required voltage range and properly limits the output current when the load exceeds the safe operating threshold.

---

## Applications

Voltage regulators with overcurrent protection are widely used in electronic systems that require stable and safe power delivery, such as:

- Embedded electronic systems
- Analog and mixed-signal circuits
- Measurement and instrumentation systems
- Laboratory power modules
- Educational and prototyping platforms

---

## Tools Used

- **OrCAD Capture** – schematic design
- **PSpice** – circuit simulation and analysis

---

## Learning Objectives

This project demonstrates several important concepts in **analog and power electronics design**, including:

- Linear voltage regulation
- Feedback control mechanisms
- Current sensing and current limiting techniques
- Protection circuits for power systems
- Analog circuit simulation and verification

---

## Author

University project developed as part of the Computer Aided Design (CAD) course, focusing on the design and simulation of analog electronic circuits.

