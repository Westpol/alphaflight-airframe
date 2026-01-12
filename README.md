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

There will be no hull or fuselage structure behind the wing. The wing itself,
together with the connecting structures, forms the primary load-bearing element
of the aircraft.

---

## Front-Mounted Motor & Nose Section

The motor is mounted at the **front of the wing**.

To support this, a dedicated **nose section** is mounted directly to the
**leading edge of the wing**. This nose section provides the structural mounting
point for the motor and propeller.

Key reasons for this approach:
- **Improved hand-launch safety**, as hands remain outside the propeller danger
  zone during launch
- Enables a **relatively flat wing configuration** without requiring elevated
  or offset motor mounts
- Simplifies the overall geometry compared to pylon-mounted solutions

The nose section exists only at the leading edge; behind it, the aircraft
continues to have no fuselage or hull.

---

## Landing & Ground Handling

### Center Skid

A **central skid** is integrated into the airframe:
- Extends approximately **5–6 cm below the underside of the wing**
- Designed to absorb ground contact during landing

Its purpose is to:
- Allow landings on **rough or uneven terrain**
- Protect the wing structure if one wing side contacts the ground first
- Reduce the likelihood of structural damage during imperfect landings

The skid acts as a protective and load-bearing element without significantly
affecting the wing layout.

---

## Control Surfaces & Stability

The aircraft will feature:
- Two ailerons for roll control
- One elevator for pitch control

A **vertical stabilizer** will be added for directional stability.  
It is currently **undecided whether this stabilizer will include a movable
rudder**. This decision will depend on later aerodynamic testing and control
requirements.

If a rudder is implemented, it will be mounted using **bearings** to ensure:
- Accurate alignment
- Low mechanical play
- Smooth and repeatable movement

---

## Preliminary Specifications

| Parameter                 | Value |
|---------------------------|-------|
| Wingspan                  | TBD   |
| Length                    | TBD   |
| Weight                    | TBD   |
| Wing Area to Weight Ratio | TBD   |

> These values will be defined once the geometry and target mass are finalized.

---

## Status

This airframe is under active development.  
Design decisions may change as the project progresses and assumptions are
validated through testing.
