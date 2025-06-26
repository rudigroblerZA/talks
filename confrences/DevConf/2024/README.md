# DevConf 2024  
## From Overheating to Overachieving — A Comedic Tale of Hacking My Car  
**Speaker:** @rudigrobler  

## Abstract
This light-hearted and technical talk chronicles how a simple overheating issue in an old Renault Kwid (2017) spiraled into a humorous deep dive into car hacking. Frustrated by unsuccessful repairs and cryptic dashboards, the speaker explores both the easy (OBD) and hard (CAN bus) ways of diagnosing and interacting with the vehicle’s systems. Along the way, attendees are introduced to concepts like CAN messaging, OBD-II protocols, and Arduino-based hardware hacking — all with plenty of laughs, lessons learned, and inspiration to tinker.

## Summary

### The Problem
- The main issue: **overheating** of a Renault Kwid (2017)
- Visits to multiple repair shops failed to fix the problem
- The car's dashboard didn’t provide useful info, despite having an 8" media screen

---

### The Plan
- Ask better questions: What’s your temperature?
- Display real data somewhere accessible
- Attempt to communicate with the car directly (hack the car)

---

### CAN Bus & OBD Concepts
- **CAN (Control Area Network):** Message-based protocol allowing ECUs (Engine, ABS, dashboard, media center) to exchange data.
- **OBD (On-Board Diagnostics):** A higher-layer protocol that provides vehicle data like speed, RPM, temperature.
- South African CO₂ tax requires these metrics to be measurable and shown somewhere.

---

### The Easy Way: OBD Adapter
- Used off-the-shelf Bluetooth OBD adapter (ELM327)
- Accessed data like temperature, speed, RPMs via smartphone apps

---

### The Hard Way: CAN Bus Hacking
- Built custom hardware (MCP2515, Arduino, RP2040)
- Used CANHacker software to send/receive CAN messages
- Collected and analyzed CAN data with car on/off
- Implemented Arduino code to send diagnostic requests

---

### Diagnosis Approach
- Analyzed:
  - Water-in vs water-out temperature
  - Coolant temperature
  - Thermostat behavior
- Compared readings to infer potential faults (akin to medical differential diagnosis)

---

### Broader Applications
- EV battery management
- Charging/upgrade planning
- Smart key systems (biometric, keyless)
- Self-driving (OpenPilot)
- Assisted driving (lane detection, parking)
- Predictive maintenance

---

### Risks + Ethical Notes
- Potential for misuse:
  - DoS attacks on vehicle networks
  - Intercepting ECU-dash messages
- Emphasized the importance of responsible tinkering

---

## Takeaways
- A mix of humor, persistence, and engineering can transform a car issue into a fun hacking journey.
- CAN bus and OBD systems are approachable for hobbyists.
- Practical lessons extend beyond fixing a car — into IoT, EVs, and more.

## Closing Quote
> “The harder I practice, the luckier I got.” — Gary Player  
