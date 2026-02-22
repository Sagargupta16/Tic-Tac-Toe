# Tic-Tac-Toe

A CSS-driven Tic-Tac-Toe game with an AI opponent -- game logic implemented entirely through CSS selectors and HTML checkbox states.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=flat&logo=githubpages&logoColor=white)

## Overview

An innovative take on the classic Tic-Tac-Toe game where the core game logic is implemented using pure CSS -- leveraging hidden checkboxes, radio inputs, and CSS sibling/state selectors to manage game state without JavaScript game logic. Features an AI opponent with selectable difficulty levels.

## Live Demo

[Play the game](https://sagargupta16.github.io/Tic-Tac-Toe/)

## Features

- **CSS-Only Game Logic** -- Game state managed through checkbox/radio input states and CSS selectors
- **AI Opponent** -- Computer player with two difficulty levels (Beginner / Advanced)
- **Player vs Computer** -- Single-player gameplay against AI
- **First Turn Selection** -- Choose whether player or computer goes first
- **Sound Toggle** -- Enable/disable game sound effects
- **Responsive Design** -- Playable on desktop and mobile devices
- **Win/Draw Detection** -- Automatic detection of game outcomes

## How It Works

The game uses a clever CSS-only approach:

1. **Hidden checkboxes** represent each cell's state (X or O)
2. **CSS `:checked` selectors** detect the current board state
3. **Sibling combinators** (`~`) propagate state changes across the board
4. **CSS animations** handle visual feedback and transitions
5. **Radio inputs** manage game settings (difficulty, first turn, sound)

## Project Structure

```
Tic-Tac-Toe/
├── index.html          # Game board, menu, and state inputs
├── style.css           # All game logic, styling, and animations
├── _config.yml         # Jekyll/GitHub Pages configuration
└── README.md
```

## Getting Started

### Play Online

Visit the [live demo](https://sagargupta16.github.io/Tic-Tac-Toe/) -- no installation required.

### Run Locally

```bash
git clone https://github.com/Sagargupta16/Tic-Tac-Toe.git
cd Tic-Tac-Toe

# Open directly in browser
open index.html

# Or use a local server
python -m http.server 8000
# Visit http://localhost:8000
```

## Gameplay

1. Select difficulty level (Beginner or Advanced)
2. Choose who goes first (Player or Computer)
3. Toggle sound on/off
4. Click on empty cells to place your mark
5. First to get three in a row wins

## License

MIT
