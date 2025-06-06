# Small-Scale Wind Turbine Controller

Built a test system for controlling and monitoring a 300 W horizontal-axis wind turbine with overvoltage protection and automated data logging.

## Hardware Design
- 24 V PM generator (H-axis turbine)
- Dump-load circuit with MOSFET control
- Arduino UNO microcontroller
- RPM sensor and voltage/current sensors

## Control Features
- Overvoltage cutoff above 32 V
- Real-time RPM and voltage monitoring
- Data logging over 10-day campus trial
- Optimized blade pitch for 9% more output

## Results
- Cut-in speed: 3.4 m/s
- Rated power: 10 m/s
- ±6% deviation from datasheet
- 5,000+ records logged over serial

## Tools Used
- Arduino IDE
- Python (PySerial)
- Excel + matplotlib for analysis

## Project Status
In Progress – Summer 2025
