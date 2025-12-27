# Project Smart Irrigation

<B> Keeping Indoor plants alive while you’re away.</B>

A practical embedded-systems project focused on automated plant care. A designed to water plants intelligently during vacations and extended travel

---

## Motivation

Plants need care and water wheather we are home or away.

 Manual watering might not be the best solution when we are on the move, frequent work trips or longer vacation ( > a week ). Asking others isn’t always an option and the worst is we might even forget despite being at home. This project aims to build a self-sufficient irrigation system that understands when a plant actually needs water rather than a fixed timer interval.

The goal is simple:

Healthy plants, even when no one is home.

---

## Evolution

|Stage | Branch                                                                       | Highlights                                               | MCU                    |
|----- | ---------------------------------------------------------------------------- | -------------------------------------------------------- | ---------------------- |
|1     | [pico-zero-V1](https://github.com/BijayKarki/project_weather/tree/pico-zero) | Reads capacitive soil sensor, waters the plant if needed | RPi-Pico-Zero (RP2040) |


Each branch represents a progression towards adding something more.<br>
**Local sensing** → **Online Sensing**.

---

## Technical Highlights

- **Microcontrollers:** Raspberry Pi Pico (RP2040), ESP32 (future)
- **Sensor:** Capacitance soil moisture
- **Actuators:** Relay-controlled water pump
- **Languages:** MicroPython
- **Interfaces:** GPIO, ADC
- **Connectivity:**
  - Local only (early branches)
  - Wi-Fi & cloud (later branches)
- **Development Tools:** Thonny, VS Code,
---


## Design Principles

- Plants first — reliability over features
- Feedback-based watering, not blind timers
- Simple systems before smart systems
- Fail-safe behavior is more important than optimization
- Scale up only after a proven long-term stability
---

## Learning Goals

- Soil moisture: sensing and calibration
- Safe relay and pump control
- Power, timing, and fault handling
- Designing systems meant to be left alone
- Building confidence in embedded decision-making
---

## Repository Structure

- smart-irrigation/
  - README.md
  - branch-xxx/
  - branch-yyy/
  - branch-zzz/
  - ...
