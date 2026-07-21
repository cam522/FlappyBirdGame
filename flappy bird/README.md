# Flappy Bird
A simple browser-based Flappy Bird clone built with HTML, CSS, and JavaScript.

## Overview
This game features:
- A bird that falls with gravity and jumps with keyboard input
- Moving pipe obstacles that scroll from right to left
- Score tracking for passing pipes
- Game over on collision with a pipe or the screen boundaries

## Files
- `index.html` — main game page
- `CSS/style.css` — layout and styling for the game
- `JS/script.js` — game logic, movement, collision detection, and scoring
- `Src/bird.gif` — bird sprite image

## How to Play
1. Open `index.html` in your browser.
2. Press `Enter` to start the game.
3. Press `ArrowUp` or `Space` to make the bird jump.
4. Avoid hitting the pipes or the top/bottom of the screen.
5. When you hit a pipe or boundary, press `Enter` to restart.

## Development
- The game logic is contained in `JS/script.js`.
- The bird and pipe collision checks are handled with bounding boxes.
- New pipes are generated continuously while the game is in play.

## Customization
You can modify the game by editing:
- `CSS/style.css` for bird size, pipe color, and layout
- `JS/script.js` for gravity, jump strength, pipe spacing, and speed

## Notes
This is a simple frontend-only game and does not require any backend or build tools.
Open `index.html` directly in a web browser to play.
