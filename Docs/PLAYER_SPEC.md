# Prime Survival
## Player Design Specification

## Overview

The player is the primary character controlled in first-person.

The controller should feel responsive, realistic, and smooth while remaining easy to learn.

---

# Perspective

- First Person

---

# Movement

The player can:

- Walk
- Run
- Jump
- Crouch
- Look around freely

Movement should include:

- Smooth acceleration
- Smooth deceleration
- Gravity
- Collision detection
- Stair support
- Slope handling

---

# Camera

Features:

- First-person camera
- Adjustable mouse sensitivity
- Smooth mouse movement
- Head bob framework
- Camera shake framework

---

# Future Features

- Swimming
- Climbing
- Crawling
- Sliding
- Leaning
- Vaulting

These systems will not be part of the initial implementation but should be considered during architecture design.

---

# Player Statistics (Future)

The player will eventually have:

- Health
- Hunger
- Thirst
- Stamina
- Temperature
- Fatigue
- Carry Weight

These statistics will remain disabled until the survival systems are implemented.

---

# Equipment (Future)

The player will eventually equip:

- Clothing
- Backpack
- Tools
- Weapons
- Flashlight

---

# Design Goals

The player should always feel:

- Responsive
- Smooth
- Predictable
- Immersive

Player controls should never fight against the player.

The environment should provide the challenge, not the controls.
