# Programmable Electronic Load (PEL) ⚡🔌

A Power Electronics project focused on designing a retrofittable Programmable Electronic Load (PEL) for safe, efficient, and controlled laboratory power testing applications.

The system was designed to provide adjustable constant-current loading using PWM-controlled power electronics while incorporating real-time current regulation and protection mechanisms.

## 🚀 Features

- Programmable constant-current electronic load
- Closed-loop PWM current regulation
- Adjustable load current control
- Real-time current sensing
- Overcurrent protection system
- LED-based fault indication
- High-frequency switching operation
- Retrofittable laboratory protection solution

## 🧠 Core Concepts

The project combines:
- AC–DC Rectification
- Buck Converter Topology
- PWM-Based Control
- MOSFET Switching
- Feedback Regulation

to achieve stable and efficient load current control independent of supply voltage variations.

## ⚙️ Technologies & Components Used

- NE555 Timer IC
- LM358 Operational Amplifier
- IRLZ44N MOSFET
- Buck Converter
- Bridge Rectifier
- Current Sensing Resistor
- PWM Control Circuit
- Proteus Simulation

## 🌐 System Architecture

The system consists of:
- AC–DC Full-Wave Bridge Rectifier
- PWM Generation Circuit
- Error Amplifier & Feedback Loop
- MOSFET Switching Stage
- Buck Converter
- Current Sensing & Protection Circuit

The load current is continuously monitored and regulated using closed-loop control.

## 🔄 Functional Workflow

1. AC input converted to DC using bridge rectifier
2. PWM signal generated using NE555 (~48 kHz)
3. LM358 compares feedback current with reference signal
4. MOSFET switching controls load current
5. Inductor smooths current waveform
6. Overcurrent condition triggers protection mechanism

## 📊 Results

- Stable current regulation achieved
- Smooth PWM-controlled current waveforms
- Fast transient response
- Reliable overcurrent protection
- Accurate current sensing using feedback circuitry
- Successful Proteus-based simulation validation

## 🛠️ Functional Modules

- PWM Generation
- Current Feedback Control
- Buck Converter Regulation
- MOSFET Switching
- Overcurrent Detection
- LED Fault Indication
- Current Sensing System

## 👨‍💻 Development

The complete system including:
- Circuit architecture
- PWM control logic
- Feedback regulation
- Protection circuitry
- Buck converter design
- Current sensing mechanisms
- Simulation and testing

was designed and implemented from scratch as part of a Power Electronics and Drives project.

## 🏫 Institution

Developed at:
- Vishwakarma Institute of Information Technology (VIIT Pune)

## 🌟 Project Goal

To develop a low-cost, efficient, and retrofittable programmable electronic load capable of protecting laboratory power electronics setups from excessive current conditions while enabling flexible and safe testing environments.
