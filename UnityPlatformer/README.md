# Simple 2D Platformer

This folder contains example scripts for a very basic 2D platformer using Unity. To use these scripts:

1. Create a new **2D** project in Unity.
2. Copy the contents of the `Assets` directory from this folder into your Unity project's `Assets` folder.
3. Create a Player GameObject and add the following components:
   - `Rigidbody2D` (set `Gravity Scale` to a suitable value, e.g. `2`)
   - `BoxCollider2D`
   - `PlayerController` script
4. Create Ground objects with `BoxCollider2D` and set their tags to `Ground`.
5. Play the scene and use the arrow keys or A/D to move. Press the space bar to jump.

These scripts provide a minimal example. You can expand on them by adding enemies, collectibles, moving platforms, etc.
