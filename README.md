# CMOS Inverter Design using LTspice

## Project Overview

This project focuses on the transistor-level design and simulation of a CMOS Inverter using LTspice as part of my Week 1 VLSI Internship at InternPe.

A CMOS Inverter is one of the fundamental building blocks of digital integrated circuits. This project explores its operation using complementary PMOS and NMOS transistors to understand the basic principles of CMOS logic design.

## Objectives

* Design and simulate a CMOS Inverter using LTspice.
* Understand PMOS and NMOS transistor operation.
* Analyze the switching behavior of a CMOS Inverter.
* Explore CMOS power consumption.
* Gain practical experience in transistor-level circuit design.

## Circuit Design

The CMOS Inverter consists of two complementary MOSFETs:

* **PMOS Transistor:** Acts as the pull-up network, connecting the output to the supply voltage when the input is LOW.
* **NMOS Transistor:** Acts as the pull-down network, connecting the output to ground when the input is HIGH.

The gates of both transistors are connected to the input, while their drains are connected to form the output.

## Working Principle

A CMOS Inverter produces an output that is the logical complement of its input.

| Input (Vin) | PMOS | NMOS | Output (Vout) |
| ----------- | ---- | ---- | ------------- |
| LOW (0)     | ON   | OFF  | HIGH (1)      |
| HIGH (1)    | OFF  | ON   | LOW (0)       |

This complementary switching operation enables CMOS logic to achieve low static power consumption under ideal steady-state conditions.

## CMOS Power Consumption

CMOS Inverters generally have low static power consumption in stable logic states. Dynamic power is consumed during switching due to the charging and discharging of internal and load capacitances.

## Tools and Technologies

* **LTspice** - Circuit design and simulation
* **CMOS Technology** - Transistor-level circuit implementation
* **PMOS and NMOS Transistors** - Complementary switching devices

## Project Structure

```text
CMOS_Inverter_LTspice/
├── CMOS_Inverter.asc
├── README.md
└── images/
    └── schematic.png
```

## Key Learning Outcomes

* Gained practical experience in CMOS transistor-level circuit design.
* Developed an understanding of PMOS and NMOS switching behavior.
* Explored the fundamental operation of CMOS logic.
* Understood the basics of static and dynamic power consumption.
* Strengthened foundational knowledge of digital VLSI design and LTspice.

## Internship Details

* **Organization:** InternPe
* **Domain:** VLSI
* **Task:** Week 1 - CMOS Inverter Design
* **Simulation Tool:** LTspice

## Author

**Amulya Thanda**
Electronics and Communication Engineering
Malla Reddy College of Engineering & Technology
