# Faraday VR

An interactive VR simulation of Faraday's Law and Lenz's Law for introductory electromagnetism, built with Three.js and WebXR for Meta Quest.

Designed and developed by Anthony Danese, high school physics teacher.

## What it does

Students move a magnetic dipole through a conducting loop and observe the induced EMF and current in real time. A floating panel displays a Lenz's Law breakdown — showing flux change direction, induced current direction, and the opposing force — so students can connect the qualitative reasoning to what they see in the scene. A freeze mechanic lets students pause the field snapshot and examine the flux state at any moment.

## Features

- Magnetic dipole with real-time field line visualization
- Conducting loop with induced EMF and current readout
- Freeze / pause mechanic to snapshot the field at any moment
- Lazy-follow floating panel with Lenz's Law breakdown
- Induced B field arrow showing opposition direction
- Field arrow grid (9×9) across the loop plane
- Visibility toggles for field components

## Controls

| Action | Control |
|---|---|
| Move magnet | Grip (right controller) + move |
| Freeze field snapshot | A button (right controller) |
| Resume | A button (right controller) again |
| Toggle field arrow visibility | B button (right controller) |
| Spin scene | Grip button + move controller |
| Walk / strafe | Left thumbstick |
| Snap turn | Right thumbstick left/right |

## How to use

1. Open your Meta Quest browser and navigate to the live sim
2. Tap **Enter VR**
3. Grab the magnet and move it toward or through the loop
4. Watch the EMF readout and Lenz's Law panel respond
5. Press A to freeze the field and examine the flux state

**Live sim:** https://phys-viz.github.io/FaradayVR/

## Pedagogical context

This simulation is designed to help students build qualitative intuition for Faraday's Law before working with quantitative flux calculations. The Lenz's Law panel is intentionally explicit — giving students precise language to describe what they observe rather than guessing. It is part of a suite of VR simulations for introductory electromagnetism.

## Tech stack

- **Three.js** r128
- WebXR API
- Vanilla JavaScript — no build tools, no frameworks
- Hosted on GitHub Pages

## License

© 2026 Anthony Danese. Licensed under **CC BY-NC-SA 4.0**.  
Free for educational use. Commercial use requires explicit written permission.
