# Hamchat

A 3D prototype game built with [Godot 4.6](https://godotengine.org/) featuring a third-person character controller, animated adventurer models, and a physics-driven world.

## Features

- 3D third-person character movement (walk, sprint, jump)
- Animated KayKit adventurer character with idle, walk, run, and jump animations
- Jolt Physics engine integration for accurate 3D physics
- Freefly (noclip) mode for development and exploration
- Mouse-captured look controls

## Controls

| Action | Key |
|---|---|
| Move | WASD / Arrow Keys |
| Jump | Space |
| Sprint | Shift |
| Freefly toggle | ² (backtick / tilde) |
| Release mouse | Escape |
| Capture mouse | Left Click |

## Project Structure

```
hamchat/
├── scenes/
│   ├── main.tscn          # Main entry scene
│   ├── world.tscn         # Game world
│   └── character.tscn     # Player character scene
├── models/
│   ├── KayKit_Adventurers_2.0_FREE/      # Character models & animations
│   ├── KayKit_Character_Animations_1.1/  # Additional animations
│   └── KayKit_FantasyWeaponsBits_1.0_FREE/ # Weapon models
├── addons/
│   ├── proto_controller/             # First-person prototype controller (Brackeys, CC0)
│   ├── playercharacter3d_template/   # PlayerCharacter3D base template
│   └── godot-jolt/                   # Jolt Physics GDExtension (v0.15.0)
└── project.godot
```

## Dependencies & Assets

- **[Godot Jolt](https://github.com/godot-jolt/godot-jolt) v0.15.0** — High-performance Jolt Physics engine as a GDExtension.
- **[KayKit Adventurers 2.0 (FREE)](https://kaylousberg.itch.io/kaykit-adventurers)** — Character models and textures by Kay Lousberg.
- **[KayKit Character Animations 1.1](https://kaylousberg.itch.io/kaykit-character-animations)** — Character animation library by Kay Lousberg.
- **[KayKit Fantasy Weapon Bits 1.0 (FREE)](https://kaylousberg.itch.io/kaykit-fantasy-weapon-bits)** — Weapon mesh assets by Kay Lousberg.
- **Proto Controller** — Prototype first-person controller by Brackeys (CC0).

## Getting Started

### Prerequisites

- [Godot Engine 4.6](https://godotengine.org/download) (Forward+ renderer)

### Running the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/LeLicorne/hamchat.git
   ```
2. Open Godot 4.6 and click **Import**.
3. Navigate to the cloned folder and select `project.godot`.
4. Click **Import & Edit**, then press **F5** (or the Play button) to run.

## License

See individual asset license files in the `models/` and `addons/` directories for third-party asset terms.
