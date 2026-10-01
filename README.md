# Wearable Multi-Sensor System

An engineering project exploring the design of an ESP32-based wearable platform for physiological and motion sensing.

## Objective

The goal is to move beyond simply wiring commercial modules together. Each sensing channel is treated as an engineering subsystem: sensing principle, body placement, signal characteristics, sampling, interface, analog front end, power, processing, calibration, and integration.

## Planned sensing domains

- Heart rate
- SpO2
- Body / skin temperature
- Motion and activity
- Hydration-related sensing (research stage)
- Additional signals where technically justified

## Development workflow

1. Build the Master Sensor Map.
2. Select and justify candidate sensors.
3. Validate sensors individually.
4. Design the embedded acquisition architecture.
5. Integrate sensors with the ESP32.
6. Develop signal-processing and data-quality checks.
7. Build the wearable prototype.
8. Connect the device to a visualization/application layer.
9. Document measurements, limitations, and engineering decisions.

## Repository structure

```text
docs/        Project context, architecture, research notes, roadmap
firmware/    Embedded firmware and sensor drivers
hardware/    Schematics, wiring, PCB and enclosure-related files
experiments/ Individual sensor experiments and validation work
analysis/    Data analysis and signal-processing notebooks/scripts
assets/      Diagrams and non-sensitive documentation images
```

## Current status

Early research and architecture phase. The system is being developed incrementally, and this repository will distinguish clearly between planned capabilities and experimentally validated results.

## Engineering principles

- Measure before claiming.
- Document assumptions and limitations.
- Prefer reproducible experiments.
- Keep hardware, firmware, and analysis modular.
- Treat power consumption and signal quality as first-class design constraints.

## Author

Nour El Islam Zougham — nanoelectronics engineering student.
