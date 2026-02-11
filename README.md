# Hyperloop Maglev (EMS) — Project

Electromagnetic suspension (EMS) maglev project focusing on coil design, sensing, and closed-loop control.
Target: stable levitation with STM32-based control and measurable performance metrics.

## Goals
- Build a lab-scale EMS maglev demonstrator
- Design coil + driver and sensing subsystem
- Implement closed-loop control (PID / state-space)
- Validate with experiments and report results

## System Overview
- Actuator: electromagnet coil + power driver
- Sensing: distance sensor (e.g., ToF / Hall / current sense)
- Controller: STM32 Nucleo (F401RE)
- Power: external supply + protection

## Repository Structure
- `docs/` – project documents (requirements, architecture, risks, timeline)
- `hardware/` – schematics, PCB, BOM
- `firmware/` – STM32/MSP430 firmware
- `software/` – simulation and tools (MATLAB/Python)
- `experiments/` – test plans and results
- `media/` – images and demo materials

## Current Status
- Planning and repository setup

## Roadmap (High-Level)
1. Requirements + safety constraints
2. Coil + driver concept and sensing selection
3. Control model and simulation
4. Firmware prototype (sensor read + PWM/driver output)
5. Bench testing + tuning
6. Final demo + report

## Links
- Portfolio: https://github.com/Bugee03/portfolio
