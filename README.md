# ASCII World

A self-contained, interactive 3D world rendered entirely with ASCII characters. Explore a grove of monoliths, pass through the stone gate, and find the floating amber beacon.

## Run

Download `index.html` and open it in a modern desktop browser. Click **Enter World** to capture the mouse. No installation, build step, network connection, or external assets are required.

## Controls

| Control | Action |
| --- | --- |
| W / A / S / D | Move forward / left / backward / right |
| Mouse | Look around |
| Shift | Run |
| Arrow keys | Look around with the keyboard |
| P | Pause or resume |
| Esc | Release the cursor and show the menu |
| Reset | Return to the starting position |

If mouse capture is unavailable, drag the scene to look around. Choose a coarse grid for better performance.

## Features

- Perspective ASCII raycasting with distance shading and occlusion
- Procedural towers, stepped trees, a stone gate, and an animated beacon
- Collision detection and an overhead minimap
- Adjustable character-grid resolution and responsive layout
- Single-file HTML, CSS, and JavaScript using native Canvas APIs

## Validation

Scripted checks cover initial rendering, animation, movement, mouse-look calculations, pause, reset, collisions, and grid resizing. Browser mouse capture depends on browser permissions and environment.
