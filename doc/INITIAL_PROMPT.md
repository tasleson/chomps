# Initial Prompt

Create a browser-based maze chase arcade game inspired by early 1980s dot-eating arcade games, using Three.js.

Do not use copyrighted Ms. Pac-Man names, sprites, sounds, maze layouts, or character designs. Create original characters, colors, level layouts, and audio.

## Game Requirements

- Use Three.js with a top-down orthographic camera.
- Render a neon arcade maze on a flat plane.
- Player controls a round yellow character with a small bow-like accent, but make the design original.
- Movement is grid-based with smooth animation.
- Arrow keys and WASD control movement.
- The player eats small pellets placed throughout the maze.
- Add larger power pellets that temporarily let the player chase enemies.
- Add 4 enemy characters with different movement behaviors:
  1. Direct chaser
  2. Ambusher
  3. Random wanderer
  4. Patrol-based enemy
- Enemies normally defeat the player on contact.
- During power mode, enemies become vulnerable and can be eaten for bonus points.
- Include tunnels on the left and right edges of the maze.
- Add score, lives, level number, and game-over UI.
- Add increasing difficulty each level.
- Add fruit/bonus items that appear temporarily.
- Include simple synthesized arcade sound effects.
- Make the code clean, modular, and contained in a single runnable HTML file.

## Technical Requirements

- Use vanilla JavaScript and Three.js from a CDN.
- No external assets.
- Generate all geometry procedurally.
- Include collision detection, pathfinding, enemy AI, pellet tracking, level reset, and win/lose conditions.
- The final answer should be a complete HTML file that can be opened directly in a browser.
