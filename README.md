# Remote-Controlled Speedboat Prototype

A hands-on hobby engineering project focused on CAD, fabrication, propulsion, control systems, and performance testing.

## Project Overview

This project involved designing, fabricating, assembling, and testing a working remote-controlled speedboat prototype. The main engineering goals were to create a lightweight hull, integrate a reliable propulsion and steering system, protect the electronics, and improve stability and maneuverability through iterative testing.

## Project Highlights

- Designed and fabricated a functional RC speedboat prototype
- Integrated motor, ESC, battery, propeller, steering, and radio-control systems
- Developed a boat-template layout for hull fabrication
- Evaluated buoyancy, stability, weight distribution, propulsion, and maneuverability
- Improved the design through practical testing and troubleshooting

## Boat Template and Design Reference

The supplied hand-drawn boat template is the reference layout for the hull geometry. The dimensions visible in the sketch should be treated as preliminary values and verified in CAD before fabrication.

| Reference dimension | Approximate value | Note |
|---|---:|---|
| Overall hull length | 600 mm | Verify against the final CAD model |
| Maximum overall width | 360 mm | Verify the widest point of the hull |
| Additional profile dimensions | 75 mm and 165 mm | Transcribed from the sketch; confirm location and units |

The original sketch should be saved in `assets/boat-template-sketch.jpg` when available. It can then be displayed here with:

```markdown
![Boat template sketch](assets/boat-template-sketch.jpg)
```

> **Fabrication note:** The sketch is a sample reference template, not a production drawing. Confirm all dimensions, clearances, material thicknesses, shaft alignment, and mounting points before cutting material.

## Hardware and Materials

The following list documents the major systems used or planned for the prototype. Exact part numbers, ratings, and dimensions should be added from the hardware labels and final build measurements.

| Component | Function | Details to document |
|---|---|---|
| Hull structure | Provides the boat body and buoyancy | Fiberglass / glass-fiber laminate or fiberglass-reinforced structure; record the final layup |
| Core or internal frame | Supports the hull and mounting points | Foam, wood, or other core material; document material and thickness |
| Motor | Produces propulsion power | Motor type, KV or RPM rating, voltage, and mounting pattern |
| ESC | Controls motor speed and direction | Current rating, input voltage, cooling method, and battery connector |
| Battery | Supplies electrical power | Chemistry, cell count or voltage, capacity, discharge rating, and runtime |
| Propeller | Converts motor power into thrust | Diameter, pitch, blade count, shaft size, and rotation direction |
| Camera | Provides onboard or FPV video | Camera model, resolution, mounting position, and power supply |
| Steering servo and rudder | Controls the boat direction | Servo torque, rudder dimensions, linkage, and steering angle |
| Radio transmitter and receiver | Provides remote control | Radio frequency, number of channels, and operating range |
| Shaft, coupling, and mount | Transfers motor torque to the propeller | Shaft diameter, coupling type, alignment, and sealing method |
| Waterproofing | Protects electronics from water | Enclosure, cable glands, sealant, and hatch sealing method |

## System Integration

The main system layout is:

```text
Battery -> ESC -> Motor -> Shaft/Coupling -> Propeller
             |
             +-> Receiver and steering servo/rudder
             +-> Camera or FPV electronics (if installed)
```

Correct battery, ESC, and motor matching is essential. Before operation, verify polarity, connector compatibility, ESC current capacity, motor cooling, propeller clearance, shaft alignment, and waterproofing.

## Testing and Performance

Testing focused on:

- Buoyancy and waterline
- Stability and weight distribution
- Propulsion response and propeller efficiency
- Steering control and turning radius
- Maximum speed and operating time
- Waterproofing and electronics protection
- Repeatability across different test conditions

Useful results to add later include measured speed, runtime, battery temperature, motor/ESC temperature, turning radius, payload, and test-water conditions.

## Project Demonstration

[Watch the RC speedboat demonstration](assets/rc-speedboat-demo.mp4)

## Repository Contents

```text
rc-speedboat-prototype/
|-- assets/
|   |-- rc-speedboat-demo.mp4
|   `-- boat-template-sketch.jpg       # add the original sketch here
|-- .gitignore
`-- README.md
```
