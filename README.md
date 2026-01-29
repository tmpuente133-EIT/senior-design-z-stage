# Optimization of In-Vacuum Z-Stage and Visualization Metrology  
**Tin–Hydrogen Interactions in an EUV Source**

## Overview
This repository documents the design, analysis, and development of an externally adjustable in-vacuum Z-stage and in-vacuum visualization system for studying tin–hydrogen (Sn–H) interactions within a vacuum vessel used to emulate conditions in an Extreme Ultraviolet (EUV) lithography source.

The project is part of the **SDSU Mechanical Engineering Senior Design Capstone Program** and is sponsored by **ASML (EUV Group, San Diego)**.

The primary objective is to improve experimental repeatability, safety, and data quality while reducing downtime associated with manual adjustments and limited visualization.

---

## Project Background
Extreme Ultraviolet (EUV) lithography systems generate light by converting microscopic liquid tin droplets into plasma using high-energy laser pulses. Post-plasma tin debris poses a contamination risk to critical optical components, particularly the collector mirror.

ASML’s *Porcupine* vacuum vessel is used to study tin–hydrogen interactions under controlled laboratory conditions. The existing experimental setup presents challenges related to:

- Manual, iterative Z-stage adjustment
- Limited positional repeatability
- Confined-space operator access
- Fixed and obstructed viewport-based visualization

This project addresses these limitations through mechanical and optical system redesign.

---

## Project Objectives
- Design an **externally adjustable Z-stage** capable of precise vertical positioning under vacuum
- Improve **repeatability and positional accuracy** of sample placement
- Eliminate the need for confined-space manual adjustments
- Develop an **in-vacuum camera system** for continuous, high-resolution monitoring
- Maintain compatibility with existing vacuum interfaces and lab control systems

---

## System Requirements (Summary)
### Z-Stage
- Vacuum compatible (materials, outgassing, thermal limits)
- Uses existing mechanical interfaces
- Vertical travel range: *< 350 mm*
- Positional accuracy: *≤ 500 µm*
- Remote operation (open-loop and closed-loop capable)
- Payload capacity: *~10 kg*

### Visualization System
- In-vacuum digital camera
- Replaceable lenses and protective lens covers
- Adjustable focal plane (manual minimum, automation preferred)
- Integration with existing data acquisition systems
- Does not obstruct operator viewports

---

## Repository Structure
```text
├── CAD/
│   ├── Assemblies/
│   ├── Part_Files/
│   └── Renderings/
│
├── Drawings/
│   ├── Manufacturing_Drawings/
│   └── Assembly_Drawings/
│
├── Analysis/
│   ├── Hand_Calculations/
│   ├── FEA/
│   └── Tolerance_Stackups/
│
├── Prototyping/
│   ├── Fabrication_Notes/
│   └── Assembly_Procedures/
│
├── Testing/
│   ├── Test_Plans/
│   ├── Experimental_Data/
│   └── Results/
│
├── Documentation/
│   ├── PDR/
│   ├── CDR/
│   └── Final_Report/
│
└── README.md
