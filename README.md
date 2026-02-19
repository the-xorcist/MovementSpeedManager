# MovementSpeedManager

**Version:** 1.0.1  
**Author:** the-xorcist  
**Release Date:** 2026-02-19

## Description

A BepInEx mod for Erenshor that provides granular control over movement speeds for different entity types. Unlike the built-in Server Admin settings which apply globally, this mod allows you to set independent speeds for players, NPCs, monsters, and SimPlayers. This enables you to increase your own movement speed without affecting AI pathfinding or making SimPlayers in your party move at different speeds than those outside your party.

## Features

- **Global Speed Control** - Set a base movement speed that applies to all entities
- **Player Speed Override** - Configure your character's movement speed independently
- **NPC/Monster Speed Override** - Control NPC and monster movement speeds separately
- **SimPlayer Speed Override** - Set movement speed for AI companions
- **Grouped SimPlayer Speed** - Special speed setting for SimPlayers in your party
- **Configurable Priority System** - Fine-grained control with fallback to global settings
- **Automatic Configuration** - Config file generated on first launch

## Installation

1. Install BepInEx for Erenshor (if not already installed)
2. Copy `MovementSpeedManager.dll` to your `BepInEx/plugins` folder
3. Launch the game
4. Edit the generated config file at `BepInEx/config/the-xorcist.movementspeedmanager.cfg` to customize speeds
5. Restart the game for changes to take effect

## Changelog

### v1.0.1 - 2026-02-19
- Initial release

---

**Note:** Source code is included in the `-source.zip` archive.
