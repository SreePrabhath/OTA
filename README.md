# Two-Stage Miller-Compensated OTA Design

## Overview

This project involves the design and analysis of a **two-stage Miller-compensated Operational Transconductance Amplifier (OTA)** using I/O (thick-oxide) devices to achieve extended voltage headroom. The design targets a specific set of performance requirements, verified through DC, AC, and transient simulations.

## Design Summary

- **Topology:** Two-stage, Miller-compensated OTA
- **Device Type:** I/O (thick-oxide) devices, chosen for extended voltage headroom

## Analysis Performed

The design was evaluated using the following simulation types:

- **DC Analysis** — to characterize gain and operating points
- **AC Analysis** — to evaluate bandwidth and phase margin
- **Transient Analysis** — to assess slew rate and dynamic behavior

## Performance Specifications

| Parameter | Target Value |
|---|---|
| DC Gain | 50 dB (320 V/V) |
| Gain-Bandwidth Product (GBW) | 30 MHz |
| Phase Margin | 52° |
| Slew Rate | 20 V/µs |
| Input Common-Mode Range (ICMR) | 0.8 V to 1.6 V |
| Load Capacitance | 2 pF |
| Power Consumption | 300 µW |

## Repository Structure

```
├── README.md
├── schematics/        # OTA circuit schematics
├── simulations/        # DC, AC, and transient simulation setups/results
└── docs/               # Design notes and reports
```

## Tools Used

- Cadence Virtuoso (schematic design and simulation)

## Status

Design completed and verified against the above specifications through simulation.

## Author

Bhargavi Katikam
M.Tech, Electronics and Electrical Communication Engineering, IIT Kharagpur
