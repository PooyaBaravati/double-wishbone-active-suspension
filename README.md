# Double Wishbone Active Suspension Design and Simulation

## Project Overview

This project presents the design, analysis, and simulation of a double wishbone active suspension system. The work combines mechanical design, structural analysis, and dynamic simulation to evaluate suspension performance under road disturbances.

The project was developed using SolidWorks for CAD modeling, SolidWorks Simulation for finite element analysis (FEA), and MATLAB Simulink/Simscape for dynamic system simulation. The objective was to investigate both the structural integrity of the suspension components and the dynamic response of the system when subjected to uneven road profiles.

---

## Main Features

* Complete double wishbone suspension CAD design in SolidWorks
* Detailed assembly including wishbones, spring, pins, supports, and connectors
* STEP export for compatibility with different CAD platforms
* Structural evaluation using finite element analysis (FEA)
* MATLAB Simulink and Simscape suspension model
* Road-bump response simulation
* Technical report and presentation documenting the development process

---

## Repository Structure

```text
.
├── cad/
│   ├── solidworks/        # SolidWorks parts and assembly files
│   └── step/              # Neutral CAD export
├── simulation/
│   └── simulink/          # Simulink model and MATLAB parameter files
├── docs/                  # Project report and presentation
├── media/                 # Images and simulation videos
├── .gitignore
└── README.md
```

---

## CAD Design

The suspension assembly was designed in SolidWorks and includes the primary mechanical components required for a double wishbone suspension configuration:

* Upper wishbone
* Lower wishbone
* Spring element
* Pins and connection components
* Mounting supports
* Complete suspension assembly

A STEP version of the assembly is included to allow viewing and inspection without requiring SolidWorks.

---

## Finite Element Analysis (FEA)

Structural evaluation was carried out using SolidWorks Simulation to assess the behavior of suspension components under representative loading conditions.

The analysis included:

* Mesh generation and refinement
* Application of boundary conditions and constraints
* Load definition based on suspension operating conditions
* Stress distribution evaluation
* Displacement analysis
* Structural performance assessment

**Note:** Due to file-size limitations and repository optimization, the complete mesh and simulation result files are not included. The repository contains the CAD models, project documentation, and representative analysis outputs necessary to understand the workflow and results.

---

## Dynamic Simulation

A MATLAB Simulink and Simscape model was developed to evaluate the dynamic behavior of the suspension system.

The simulation investigates:

* Vehicle response to road disturbances
* Suspension displacement
* Dynamic system behavior over bump inputs
* Comparison of suspension performance under varying operating conditions

Relevant files:

* `simulation/simulink/suspension_control_4.slx`
* `simulation/simulink/suspension_parameters.m`

---

## Documentation

The documentation folder contains:

* Technical project report
* Presentation slides

These documents describe the design methodology, suspension theory, structural analysis approach, simulation setup, and project conclusions.

---

## Software Used

* SolidWorks
* SolidWorks Simulation
* MATLAB
* Simulink
* Simscape

---

## Author

**Pooya Zare Baravati**

MSc Student in Autonomous Vehicle Engineering

---

## Notes

This repository is intended for academic and portfolio purposes. Large simulation databases and detailed FEA result files have been excluded to maintain a lightweight and accessible repository. The included files provide a complete overview of the design, analysis, and simulation workflow used throughout the project.
