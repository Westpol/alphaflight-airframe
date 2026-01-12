# Alphaflight Airframe

This repository contains the CAD files and design notes for an experimental
fixed-wing FPV airframe intended to be flown with the Alphaflight firmware.
The long-term goal is fully autonomous flight.

This is a personal project and primarily serves as documentation of the design
and iteration process.

---

## Software Used

The airframe is designed using **FreeCAD** (free and open-source).  
Current version in use: **1.0.2**

---

## Core Design Concept

The current concept is a fixed-wing aircraft without a traditional fuselage.
Instead, carbon fiber tubes connect the wing to the tail section, keeping the
structure lightweight, modular, and easy to iterate.

### Front-Mounted Motor & Nose Section

The motor is mounted at the **front of the wing**.  
To enable this safely and cleanly, a dedicated **nose section** extends from the
wing’s trailing edge to the leading edge.

This design has several advantages:
- **Improved hand-launch safety**: hands remain completely outside the propeller
  danger zone during launch.
- **Flatter wing geometry**: no need to raise or offset the wing to clear the
  propeller.
- **Cleaner airflow** compared to elevated or pylon-mounted motors.

Overall, this is a more robust and pilot-friendly solution than mounting the
motor above the wing.

---

## Landing & Ground Handling

### Center Skid

A **central skid** is integrated into the airframe:
- Extends **5–6 cm below the underside of the wing**
- Designed to absorb ground contact during landing

Purpose:
- Allows landings on **rough or uneven terrain**
- Protects the wing structure if one wing tip contacts the ground first
- Reduces structural stress on the wing during imperfect landings

This skid effectively acts as a sacrificial and load-bearing element, improving
durability without significant aerodynamic compromise.

---

## Control Surfaces

The aircraft will feature:
- Two ailerons for roll control
- One elevator for pitch control
- One or more rudders for yaw control

### Rudder Mounting

The rudder(s) will be **mounted using bearings** to ensure:
- Perfect alignment
- Minimal play
- Extremely smooth movement

This is done deliberately to achieve a **high-quality, precise control feel**.
No sloppy foam-hinge nonsense here — the goal is mechanical correctness and a
premium flight experience.

---

## Preliminary Specifications

| Parameter                 | Value |
|---------------------------|-------|
| Wingspan                  | TBD   |
| Length                    | TBD   |
| Weight                    | TBD   |
| Wing Area to Weight Ratio | TBD   |

> These values will be filled in once the geometry and target mass are finalized.

---

## Status

This airframe is under active development.  
Expect frequent changes as design assumptions are validated (or disproven).

Feedback, critique, and engineering nitpicks are always welcome.
