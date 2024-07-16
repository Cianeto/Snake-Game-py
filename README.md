# Personal Project: Snake Game made with pygame.

The objective of this repository is to have fun and improve my coding skills while at it.

## 1. Features Summary

### - Title Screen

- The game should open in its own window. It starts on the game title screen, here you have the following options: **Start**, **Options**, **Exit**.

- There's also a scoreboard that logs the highest score and the last {1-10} games score.

### - Start

- Initializes the game round.

- Gameplay

  - Snake moves automatically in a direction, player can change its direction by pressing 'WASD' (e.g. snake is going left: pressing 'W' makes it go up and 'S' makes it go down. In this scenario, 'A' and 'D' doesn't do anything).

  - If 'snake head' 'touches' 'apple', its 'body' increases in size and another 'apple' spawns in a random location.

  - If 'snake head' 'touches' 'wall' or its own 'body', it's game over (brought back to menu).

  - Round runs indefinitely until game is forcefully closed, game is paused by pressing 'ESC', or game over is triggered.

### - Options

- Sliders {0-100%} for sound config (SFX and BGM).
- Radio buttons for Windowed, Borderless or Fullscreen.
- Select option for choosing game theme (skin).

### - Exit

- Terminates game process.

## 2. To-do

- [ ] First Step

  - [ ] Define files structuring.

  - [ ] Figure out how to implement pygame lib.

  - [ ] Run my first windowed UI.
