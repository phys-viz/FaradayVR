# Faraday VR

An interactive VR simulation of Faraday's Law and Lenz's Law for introductory electromagnetism, built with Three.js and WebXR for Meta Quest.

Designed and developed by Anthony Danese, high school physics teacher.

## What it does

Students hold a bar magnet (right controller) and move it through a conducting loop floating in space in front of them. A 7×7 grid of magnetic field arrows updates in real time as the magnet moves. A lazy-follow floating panel displays a Lenz's Law breakdown — flux change direction, induced B direction, and induced current direction — in plain language. A freeze mechanic lets students snapshot the entire field state and examine it hands-free, with a full qualitative breakdown appearing on the panel.

## Features

- Bar magnet attached to right controller — full 3D freedom of movement
- 7×7 magnetic field arrow grid across the loop plane, color-coded by field direction
- Conducting loop with live induced current markers showing direction and magnitude
- Loop glow disc that tracks flux magnitude and direction
- Freeze mechanic — snapshots magnet position, field, current, and panel simultaneously
- Smooth magnet return to controller on unfreeze (0.5s lerp)
- Lazy-follow floating panel, always in front of the player at reading height
- Active panel: flux direction + current direction + EMF strength bar
- Frozen panel: full Lenz's Law breakdown — magnet motion → flux → induced B → induced current
- Polarity flip with correct N/S label and field response
- Haptic feedback proportional to EMF magnitude
- Desktop preview mode with auto-animating magnet (no headset required)

## Controls

| Action | Control |
|---|---|
| Move magnet | Right controller — move freely |
| Freeze field snapshot | Index trigger (right controller) |
| Unfreeze / resume | Index trigger (right controller) again |
| Flip magnet polarity | Button A (right controller) |

## How to use

1. Open your Meta Quest browser and navigate to the live sim
2. Tap **Enter VR**
3. Hold the right controller — this is your magnet
4. Move the magnet toward and through the loop
5. Watch the field arrows, current markers, and panel respond
6. Press the index trigger to freeze the snapshot and read the Lenz's Law breakdown
7. Press the index trigger again to resume — the magnet smoothly returns to your hand

**Live sim:** https://phys-viz.github.io/FaradayVR/

## Pedagogical context

This simulation is designed to help students build qualitative intuition for Faraday's Law before working with quantitative flux calculations. The freeze mechanic is the core pedagogical affordance — students make a deliberate gesture to pause, look at the field state, and read the causal chain: what the magnet is doing, how the flux is changing, what the induced field must do to oppose that change, and which way the current flows. The Lenz's Law panel uses precise language intentionally, giving students the vocabulary to describe what they observe rather than paraphrasing it.

This simulation is part of a suite of VR simulations for introductory electromagnetism hosted at [phys-viz.github.io](https://phys-viz.github.io).

## Tech stack

- **Three.js** r128
- WebXR API
- Vanilla JavaScript — no build tools, no frameworks
- Hosted on GitHub Pages

## License

© 2026 Anthony Danese. Licensed under **CC BY-NC-SA 4.0**.  
Free for educational use. Commercial use requires explicit written permission.
