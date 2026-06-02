System Architecture
System Ibjective
- Simulate a simplified EV BMS using Arduino-based
  ADC acquisition and real-time display output.

High-Level Flow
Voltage Input -> ADC Acquisition -> SOC Estimation -> Display UI -> Serial Logging

Function Modules
- ADC Module: Read analog voltage values
- SOC Estimator: Convert voltage into battery percentage
- Display UI: Display real-time voltage and battery percentage
- Serial Logger: Output debug information to serial monitor
