# System Architecture — Hyperloop EMS Maglev

## 1. High-Level Overview

The system consists of:

- Electromagnetic actuator (coil + driver)
- Position sensing subsystem
- STM32-based controller (Nucleo F401RE)
- Power supply and protection
- Mechanical levitation structure

---

## 2. Functional Blocks

### 2.1 Actuator
- Electromagnetic coil
- MOSFET driver stage
- Current control

### 2.2 Sensing
- Distance sensor (ToF / Hall / optical)
- Current measurement (shunt + amplifier)

### 2.3 Controller
- MCU: STM32F401RE
- ADC: position + current measurement
- PWM: coil control
- UART: debugging

### 2.4 Control Strategy
- Closed-loop control
- PID or state-space control
- Stability region analysis

---

## 3. Signal Flow

Sensor → ADC → Control Algorithm → PWM → Driver → Coil → Magnetic Force → Levitation Gap

---

## 4. Next Steps

- Define physical parameters
- Select sensing method
- Create mathematical model
- Simulate in MATLAB
