# Chomps

Chomps is a browser maze-chase arcade game inspired by early 1980s dot-eating games. It is built with Three.js, procedural neon maze geometry, and Web Audio API sound effects.

## TL;DR I just wanna play it now!

https://tasleson.github.io/chomps/chomps.html

## Play locally

Open `index.html` through a local web server to view this README and play the game in an embedded window.

```sh
python3 -m http.server 8087
```

Then visit:

```text
http://127.0.0.1:8087/
```

You can also open `chomps.html` directly through the same server for a full-window game view.

## Controls

- `Enter`: start, continue, or restart from the overlay
- `Arrow keys` or `WASD`: move through the maze
- `R`: restart after game over

## Gameplay

- Eat every spark in the maze to clear the level.
- Grab surge cores to turn enemies vulnerable for a short time.
- Chomp vulnerable enemies for escalating bonus points.
- Use the left and right tunnels to wrap across the maze.
- Collect temporary bonus gems when they appear.
- Clearing a maze starts a faster, more dangerous level.

## Features

- Procedural randomized neon maze
- Four enemy behaviors: direct chaser, ambusher, random wanderer, and patrol enemy
- Smooth grid movement with collision detection and pathfinding
- Pellets, power pellets, bonus items, score, lives, levels, and game over state
- Synthesized arcade sounds with the Web Audio API
- No image or audio assets

## GitHub Pages

For GitHub Pages, publish the repository root. `index.html` is the project page and embeds `chomps.html` in a playable frame.
