# Tic-Tac-Toe  
A simple, single-file browser game for playing Tic-Tac-Toe with a dark-themed UI.

## Description  
Tic-Tac-Toe is a classic 3x3 grid game implemented entirely in a single HTML file using vanilla JavaScript, CSS, and HTML. It provides an interactive UI for two players to take turns marking X and O, tracks scores across multiple rounds, and visually highlights winning lines. This project serves casual players who want a lightweight, dependency-free browser game without any setup.

## Features  
- Interactive 3x3 Tic-Tac-Toe board using CSS Grid  
- Turn-based gameplay alternating between X and O  
- Win detection with visual highlight on winning cells  
- Draw detection with status update  
- Score tracking for X and O across multiple rounds (resets on page reload)  
- "New Game" button to restart the board without resetting scores  
- Responsive dark-themed UI with hover and click animations  
- All game logic, styles, and markup contained in a single `index.html` file  

## Tech Stack  

| Technology       | Role                      |
|------------------|---------------------------|
| HTML             | Markup and structure      |
| CSS (Grid)       | Styling and layout        |
| JavaScript       | Game logic and interactivity |

## Architecture  
This project is a single-page application contained entirely within one file: `index.html`. It combines markup, styles, and JavaScript logic in a modular fashion using scoped variables and functions. The game state (board array, turn, scores) is managed in JavaScript variables, with DOM manipulation used to render the board and update UI elements dynamically. There are no external dependencies or build steps.

## Prerequisites  
- A modern web browser (Chrome, Firefox, Edge, Safari) with JavaScript enabled  
- No additional tools or installations required  

## Installation & Setup  
No installation is necessary. To run the game:  
1. Download or clone the repository containing `index.html`.  
2. Open `index.html` in any modern web browser.

## Running  
### Development  
Open `index.html` directly in a browser. Changes can be made by editing the file and refreshing the page.  

### Production  
Simply serve `index.html` via any static file server or open it locally in a browser. No server or build process is needed.

## Docker  
No Docker or containerization configuration is provided or required.

## API Overview  
No backend or API routes exist; this is a purely frontend browser game.

## Environment Variables  

| Variable | Description | Required |
|----------|-------------|----------|
| *None*   | This project does not use environment variables. | No |
