# Prime Survival
## Technology Stack

## Purpose

This document defines the software, file formats, and technical standards used to develop Prime Survival.

---

# Game Engine

**Engine:** Godot 4 (Latest Stable Version)

Reason:
- Free and open source
- Excellent 3D support
- GDScript for rapid development
- Cross-platform export
- Strong community

---

# Programming Language

**Language:** GDScript

Reason:
- Native to Godot
- Easy to learn
- Fast iteration
- Excellent editor integration

---

# Version Control

- Git
- GitHub

Purpose:
- Track changes
- Collaborate
- Restore previous versions
- Manage releases

---

# 3D Assets

Preferred format:

- .glb

Reason:
- Best compatibility with Godot
- Supports animations
- Supports materials
- Compact file size

---

# Textures

Preferred formats:

- .png (lossless)
- .webp (optimized where appropriate)

Guidelines:
- Use power-of-two resolutions (512, 1024, 2048, 4096).
- Compress textures where quality allows.

---

# Audio

Preferred formats:

- .ogg (music and ambient audio)
- .wav (short sound effects)

---

# Materials

Use Godot's StandardMaterial3D unless custom shaders are required.

---

# Source Control Rules

Commit often.

Each commit should:
- Have one clear purpose.
- Build successfully.
- Not introduce unrelated changes.

---

# Target Platforms

Primary:
- Windows
- Linux
- Android

Future:
- Steam
- Steam Deck

---

# Performance Goals

Desktop:
- 60 FPS target

Android:
- 30–60 FPS depending on device capability

---

# Asset Naming Convention

Examples:

Player.glb

OakTree_01.glb

Rock_03.glb

River_Ambience.ogg

Campfire.wav

Grass_Albedo.png

Avoid spaces in file names.

Use descriptive names.

---

# Development Philosophy

Use free and open-source tools wherever practical.

Build modular systems.

Optimize continuously.

Document major technical decisions.

Design every system with future multiplayer support in mind.
