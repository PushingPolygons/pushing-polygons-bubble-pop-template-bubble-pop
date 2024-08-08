# Bubble Pop
A simple [Godot](https://godotengine.org/) project to learn about 2D sprite movement and mouse clicking.

## Instructions
The project instructions begin here - [Bubble Pop: 1. Project Setup](https://gitlab.com/kirkja-leikjahonnunar/knowhow/-/blob/main/Tinker/Drills/Bubble%20Pop/1.%20Project%20Setup/README.md).

## GDScript Topics
- Variables.
- Functions.
- Event Signals.

### Important Nodes, Properties, and Functions

#### `Node`
- Parent Node: `get_parent()`
- Spawn: `PackedScene.instantiate()`
- De-spawn: `queue_free()`
- Player mouse input.

#### `Node2D` / `Area2D`
- 2D Transformation properties:
  - `Node2D.position.x`
  - `Node2D.position.y`
  - `Node2D.rotation`
  - `Node2D.scale.x`
  - `Node2D.scale.y`

#### `CollisionShape2D`
- `Inspector` > `CollisionShape2D` >`Shape`

#### `Sprite2D`
- `Inspector` > `Sprite2D` > `Texture`

#### `Timer`
- Signal: `time_out`
