# Prime Survival
## Coding Standards

This document defines the coding standards for the Prime Survival project.

---

# Goals

- Keep the code clean and easy to understand.
- Make every script responsible for one task.
- Build reusable systems.
- Keep future multiplayer support in mind.

---

# Naming Conventions

## Files

Use PascalCase.

Examples:

- PlayerController.gd
- WorldManager.gd
- InventorySystem.gd

---

## Variables

Use snake_case.

Example:

player_speed
current_health
camera_rotation

---

## Functions

Use snake_case.

Example:

move_player()
update_weather()
save_game()

---

## Constants

Use ALL_CAPS.

Example:

MAX_HEALTH
DEFAULT_SPEED
GRAVITY

---

# Script Responsibilities

Each script should have one responsibility.

Good examples:

- Player movement
- Camera control
- Inventory
- Weather
- Audio

Avoid putting unrelated systems into the same script.

---

# Comments

Only add comments where they help explain complex logic.

Do not comment obvious code.

---

# Folder Organization

Assets/
Scenes/
Scripts/
Resources/
Shaders/
Docs/

Each file should be stored in the appropriate folder.

---

# Future Multiplayer

Avoid writing systems that depend directly on one specific player.

Instead, design systems so they can support multiple players in the future with minimal changes.

---

# Performance

- Reuse objects where possible.
- Avoid unnecessary processing every frame.
- Keep scripts modular.
- Use Godot signals to reduce coupling between systems.

---

# Version Control

Commit changes frequently.

Each commit should focus on a single feature or improvement.

Write clear commit messages describing the change.
