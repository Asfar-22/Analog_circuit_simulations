# 555 Timer Astable Multivibrator (1 Hz)

## Overview

This project demonstrates the design and simulation of a **1 Hz Astable Multivibrator** using the **NE555 Timer IC** in **Proteus Professional**.

The circuit is designed to generate a continuous square wave with a frequency of approximately **1 Hz**, making it suitable for timing applications, LED blinking, pulse generation, and educational demonstrations of analog electronic circuits.

---

## Objectives

* Design a 1 Hz square wave generator using the NE555 Timer.
* Simulate the circuit in Proteus Professional.
* Verify the output frequency using a frequency counter.
* Analyze the circuit using standard 555 Timer equations.

---

## Software Used

* Proteus Professional

---

## Components Used

| Component         | Description                               |
| ----------------- | ----------------------------------------- |
| NE555             | Timer IC                                  |
| Resistors         | Timing network                            |
| Potentiometer     | Frequency adjustment                      |
| Capacitors        | Timing capacitor and decoupling capacitor |
| LED               | Output Indicator                          |
| Frequency Counter | Output frequency measurement              |
| DC Power Supply   | 5 V                                       |

---

## Theory

The NE555 Timer is configured in **Astable Mode**, where it continuously switches between charging and discharging the timing capacitor.

The output is a continuous square wave whose frequency depends on the resistor and capacitor values.

### Frequency Equation

[
f=\frac{1.44}{(R_A+2R_B)C}
]

where

* (R_A) = Timing resistor
* (R_B) = Timing resistor / potentiometer
* (C) = Timing capacitor

---

## Repository Structure

```
1Hz/
│
├── Proteus/
│   └── 555-Timer-1Hz.pdsprj
│
├── Images/
│   ├── Circuit.png
│   ├── Waveform.png
│
├── Calculations/
│   └── Design_Calculations.pdf
│
└── README.md
```

---

## Circuit Diagram

The complete circuit schematic is available in the **Images** folder.

---

## Simulation Results

The circuit successfully generates a square wave close to **1 Hz**.

The simulation verifies:

* Stable oscillation
* Approximately 1-second period
* Continuous square-wave output
* Correct frequency measurement using the frequency counter

---

## Applications

* LED Blinking Circuit
* Clock Pulse Generator
* Timer Circuits
* Pulse Generator
* Educational Electronics Experiments

---

## Future Improvements

* Hardware implementation on a breadboard
* PCB design
* Adjustable frequency control
* Duty cycle optimization

---

## Author

**Asfar**

Electronics and Communication Engineering (ECE)

---

## License

This project is licensed under the MIT License.
