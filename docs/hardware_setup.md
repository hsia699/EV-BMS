# Hardware Setup

# Hardware Overview

This project uses a Arduino-based embedded platform to simulate a simplified EV BMS.
The hardware setup focuses on:
- Analog voltage acquisition
- Real-time display output
- SOC estimation
- Embedded system validation
- Serial debug logging

# Hardware Components
- Arduino Uno: Main embedded controller
- LCD Display: Battery status visualization
- Breadboard: Prototyping
- Jumper Wires
- DC Power Supply: Simulated battery voltage source
- USB Cable
- 1k ohms Protection Resistor

# System-Level Hardware Flow
DC Supply -> Arduino ADC Input(A0) -> Voltage Processing -> SOC Estimation -> LCD Display -> Serial Debug Logging
