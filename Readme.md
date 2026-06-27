# AI-Assisted PLL IP Design using SKY130

![Status](https://img.shields.io/badge/Status-In%20Progress-blue)
![PDK](https://img.shields.io/badge/PDK-SKY130-green)
![EDA](https://img.shields.io/badge/EDA-xschem%20%7C%20ngspice%20%7C%20Magic-orange)
![License](https://img.shields.io/badge/License-Apache--2.0-blue)

---

## Project Overview

This repository documents the complete design and verification flow of a Phase Locked Loop (PLL) using the open-source SKY130 Process Design Kit (PDK).

The work is carried out as part of the **VSD AI-Assisted PLL Design Internship**, where Artificial Intelligence tools such as ChatGPT are used to assist in understanding, designing, debugging, documenting, and verifying each PLL building block.

Unlike a conventional project repository, this repository focuses on documenting the complete engineering workflow, including AI prompts, design iterations, simulations, observations, debugging, and future improvements.

---

# Objectives

The primary objectives of this project are:

- Understand PLL architecture
- Study phase and frequency locking
- Design individual PLL building blocks
- Simulate circuits using ngspice
- Create schematics using xschem
- Verify functionality before layout
- Learn SKY130 analog device usage
- Document AI-assisted engineering workflow
- Maintain a professional GitHub repository

---

# PLL Architecture

```

Reference Clock
│
▼
Phase Frequency Detector (PFD)
│
▼
Charge Pump
│
▼
Loop Filter
│
▼
Voltage Controlled Oscillator (VCO)
│
▼
Frequency Divider
│
└───────────────────────────────┐
│
└──────────── Feedback ──────────┘

```

---

# Repository Structure

```

VSD_PLL_IP_DESIGN
│
├── docs/
├── Week_01/
├── Week_02/
├── Week_03/
├── xschem/
├── spice/
├── simulations/
├── layouts/
├── assets/
├── AI_Prompts/
├── Reports/
├── Scripts/
└── References/

```

---

# Design Flow

```

Literature Review

↓

PLL Theory

↓

Circuit Design

↓

xschem Schematic

↓

SPICE Netlist

↓

ngspice Simulation

↓

Waveform Analysis

↓

Debugging

↓

Documentation

↓

GitHub Update

```

---

# Tools Used

| Tool | Purpose |
|------|----------|
| xschem | Schematic Capture |
| ngspice | Circuit Simulation |
| SKY130 PDK | Semiconductor Technology |
| Magic | Layout Design |
| Git | Version Control |
| GitHub | Repository Hosting |
| ChatGPT | AI Assisted Design |
| Linux | Development Environment |

---

# Weekly Progress

## Week 1

- [x] Literature Review
- [x] Reference Paper Study
- [x] PLL Fundamentals

---

## Week 2

- [ ] PLL Theory
- [ ] Phase Frequency Detector
- [ ] Charge Pump
- [ ] Loop Filter

---

## Week 3

- [ ] Voltage Controlled Oscillator
- [ ] Frequency Divider
- [ ] PLL Integration
- [ ] Lock Analysis
- [ ] Jitter Study

---

# AI Assisted Workflow

Every circuit block developed in this project includes

- AI Prompt
- Generated Circuit
- Manual Verification
- Simulation
- Debugging
- Engineering Observation

This enables reproducibility while ensuring that all AI-generated content is verified through simulation.

---

# Repository Status

Current Stage

> Environment Setup Completed

Current Focus

> Phase Frequency Detector (PFD)

---

# References

1. SKY130 Open PDK
2. OpenLane Documentation
3. xschem Documentation
4. ngspice User Manual
5. Reference PLL Repository
6. IEEE Research Papers

---

# Author

Raj Joshi

B.Tech Electronics and Communication Engineering

AI Assisted PLL Design Internship

VLSI System Design (VSD)

---

## License

Apache License 2.0