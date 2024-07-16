# Personal Project: Snake Game made with pygame.

The objective of this repository is to have fun and improve my coding skills while at it. I've divided the planning of what i shall do in three steps: In the first step I'll get to know pygame, in the second step I'll start coding the base of the game, and in the third I'll polish it.

## 1. Features Summary

### - Title Screen

- The game should open in its own window. It starts on the game title screen, here you have the following options: **Start**, **Options**, **Exit**.

- There's also a scoreboard that logs the highest score and the last 5 games score.

### - Start

- Initializes the game round.

- Gameplay

  - **Snake** moves automatically in a direction, player can change its direction by pressing 'WASD' (e.g. snake is going left: pressing 'W' makes it go up and 'S' makes it go down. In this scenario, 'A' and 'D' doesn't do anything).

  - If **snake head** touches **apple**, its **body** increases in size and another **apple** spawns in a random location.

  - If **snake head** touches **border** or its own **body**, it's game over (brought back to menu).

  - Game instance runs indefinitely until game is forcefully closed, game is paused by pressing 'ESC', or game over is triggered.

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

- [ ] Second Step

  - [ ] Implement game title with the option to start a game round or exit the game.

  - [ ] Implement playing board, snake positioning, movement control, gameover by touching border of the board.

  - [ ] Implement apple random spawn, snake body size mechanic, game over on touching its own body mechanic.

  - [ ] Implement display of score tracker and highest score during a game round, scoreboard of the last 5 tries and highest score on the game title.

- [ ] Third Step

  - [ ] Add a 'Settings' option in the main menu, between 'Start' and 'Exit'. It opens settings menu, in which there will be the options for **Sound** config, **Window Mode** config and **Game Theme** config.

  - [ ] Implement sounds for: Game Start, Eating apples, Game Over. Add background music. Implement sound adjustment as a slider (0-100%) in the settings, one slider for SFX, one for BGM and a checkbox for muting all sound above these two sliders.

  - [ ] Implement three radio buttons for Window Mode setting: Windowed, Borderless, Fullscreen.

  - [ ] Beautify the base game appearance and add the option to change between the Default skin theme and a custom theme mean't for the luls (I'll hardcode this feature, probably).
