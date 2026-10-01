# Roadmap

## Phase 0 — Requirements and sensor map
- Define target physiological/motion measurements.
- Build the Master Sensor Map.
- Record signal type, expected range, sampling rate, interface, body placement, and AFE needs.

## Phase 1 — Individual sensor validation
- Test one sensor at a time.
- Record raw data and noise behavior.
- Document wiring, firmware, power draw, limitations, and failure cases.

## Phase 2 — Embedded integration
- Standardize sensor drivers and sampling.
- Integrate multiple sensors on the ESP32.
- Add timing, buffering, and basic data-quality checks.

## Phase 3 — Wearable prototype
- Design power architecture and enclosure strategy.
- Validate comfort, placement, repeatability, and battery life.

## Phase 4 — Processing and application layer
- Add signal processing and derived metrics only when validated.
- Build a lightweight dashboard/app for visualization and logging.

## Phase 5 — Evaluation
- Compare measurements against suitable references where possible.
- Quantify limitations and identify the next hardware iteration.
