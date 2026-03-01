# Tic-Tac-Toe

Single-file browser game. Vanilla HTML/CSS/JS, no build tools, no dependencies.

## Structure

- `index.html` — Everything. Game logic, styles, and markup in one file.

## Tech

- Vanilla JavaScript (no framework)
- CSS Grid for the 3x3 board
- Dark theme (#0f0f0f background)
- No external dependencies

## Game Logic

- 3x3 board stored as flat array of 9 cells
- WIN_LINES constant defines all 8 winning combinations
- Turn alternates between X and O
- Score tracked across games (persists until page reload)
- Win detection highlights winning cells with green border

## Conventions

- All state in module-scoped variables (board, turn, gameOver, scores)
- DOM manipulation via createElement + event listeners
- Minimal CSS with transitions for hover/click feedback
