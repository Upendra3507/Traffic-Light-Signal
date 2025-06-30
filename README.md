# 🚦Traffic Signal Light using 555 Timer IC

## 📝 Project Overview
The Traffic Light Signal using 555 Timer IC is a basic electronics project that mimics the operation of a real-world traffic signal system using simple components. The project is designed to control three LEDs (Red, Yellow, and Green), which represent stop, ready, and go signals respectively. By utilizing the 555 Timer IC in astable mode, the circuit generates timed pulses that are fed into a decade counter IC (like 4017) to sequentially activate the LEDs. Each light turns on for a specific duration, simulating the timing cycles used in actual traffic lights at road intersections.

This project demonstrates fundamental principles of:

- Digital timing and sequencing

- Astable multivibrator behavior of the 555 timer

- Basic traffic control logic

## 🎯 Objectives
- To simulate a traffic signal system using simple timer circuits.

- Understand the working of 555 Timer IC in astable mode.

- Develop practical skills in wiring, simulation, and timing control.

## ⚙ Tools & Components Used

- **2 × 555 Timer ICs**
- **3 × LEDs** (Red, Yellow, Green)
- **Resistors:** 100Ω, 470Ω, 100kΩ
- **Capacitors:** 10µF, 100µF
- **9V Battery**
- Breadboard & Connecting wires
- 
## ⚡ Working Principle

- Two 555 Timer ICs are used in cascade, both configured in **Astable mode**.

- The **first timer** controls when the *second timer* is powered on.

- The **second timer's output** determines which LED is turned on:
  - **Green LED** turns ON first.
  - After a delay, **Yellow LED** turns ON.
  - Then **Red LED** is activated before the cycle repeats.
- The **delay time** is calculated using the standard astable formula:
T = 0.693 × (RA + 2RB) × C

## 🖼 Circuit Diagram

![image alt](https://github.com/Upendra3507/Traffic-Light-Signal/blob/bd9e7470b577f90825aabdc992e0cf71224cc643/Circuit.jpg)

## 🧑‍💻 Author

**Upendra Kurni**  
B.Tech in Electronics and Communication Engineering  
RGMCET, Nandyal
