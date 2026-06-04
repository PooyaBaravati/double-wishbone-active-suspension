# Double Wishbone Active Suspension Design and Simulation

This repository presents a double wishbone active suspension project combining **CAD design**, **finite element / mesh-based structural analysis**, and **MATLAB Simulink / Simscape simulation** of suspension response over road disturbances.

## Project Overview

The project focuses on the development of an electromechanical active suspension concept. It includes a SolidWorks model of a double wishbone suspension assembly, a mesh/stress-analysis workflow, and a Simulink model used to study the suspension behavior in a bumpy-road situation.

## Main Features

- Double wishbone suspension CAD assembly designed in SolidWorks
- Upper and lower wishbone components, spring, pins, top/base supports, and full assembly
- STEP export for easier viewing in other CAD software
- Mesh and stress-analysis workflow for structural evaluation
- MATLAB Simulink / Simscape suspension model
- Road bump response simulation for passive/active suspension behavior
- Project report and presentation included for documentation

## Repository Structure

```text
.
├── cad/
│   ├── solidworks/        # SolidWorks parts and assembly files
│   └── step/              # Neutral CAD export
├── simulation/
│   └── simulink/          # Simulink model and MATLAB parameters
├── docs/                  # Report and presentation
├── media/                 # Images and animation/video
├── .gitignore
└── README.md
```

## CAD Design

The CAD model was created in SolidWorks and includes the main mechanical components of the suspension system:

- Upper wishbone
- Lower wishbone
- Upright / knuckle-related parts
- Spring component
- Pins and connectors
- Full assembly

The `Assem1.STEP` file is included so the model can be opened without SolidWorks in many CAD viewers.

## Simulation

The Simulink model studies suspension response to road disturbances. The model includes suspension parameters and is intended to compare body displacement and suspension behavior when the system is exposed to a bump input.

Relevant files:

- `simulation/simulink/suspension_control_4.slx`
- `simulation/simulink/suspension_parameters.m`

## FEA / Mesh Analysis

The project includes a mesh-based stress-analysis workflow in SolidWorks Simulation. The analysis focuses on checking whether the suspension components can withstand operational loads and road disturbance effects.

Key analysis aspects:

- Mesh refinement of critical regions
- Boundary conditions and fixtures
- Loading based on vehicle mass distribution
- Stress and displacement evaluation
- Factor of safety considerations

## Documentation

The `docs/` folder contains:

- Full project report
- Presentation slides

These files explain the design concept, active suspension background, CAD development, FEA setup, and Simulink simulation results.

## Software Used

- SolidWorks
- SolidWorks Simulation
- MATLAB
- Simulink / Simscape

## Author

Pooya Zare Baravati

## Notes

This project was developed as an academic mechanical design and simulation project. Binary CAD and simulation files are included for portfolio and review purposes.
