# Basic Tic Tac Toe Game

A simple Tic Tac Toe game developed using **HTML**, **CSS**, and **JavaScript**. This project allows two players to play Tic Tac Toe on a 3x3 grid with basic functionality for detecting wins and resetting the game.

---

## Features

- Two-player turn-based gameplay (Player O and Player X)
- Detects winner based on classic Tic Tac Toe winning patterns
- Displays winner message upon game completion
- Buttons to reset or start a new game
- Disables clicked boxes to prevent overwriting moves

---

## How It Works

- Players take turns clicking empty cells on the grid.
- After each move, the game checks if there's a winner by comparing the cells with predefined winning patterns.
- When a player wins, a congratulatory message is displayed and further clicks are disabled.
- The **Reset** and **New Game** buttons allow the game board to be cleared and a new game started.

---

## Code Overview

### JavaScript Highlights

- `turn0` boolean to track current player (`true` for O, `false` for X).
- `winpattern` array contains all possible winning cell combinations.
- `checkwinner()` function iterates over winning patterns to detect if a player has won.
- `disableboxes()` and `enableboxes()` functions control user interaction on the board.
- Event listeners on each box handle player moves.
- Event listeners on reset buttons to clear the game state.

---

## Usage

1. Open `index.html` in any modern browser.
2. Click on any empty box to place your mark.
3. Players alternate turns automatically.
4. Watch for the winner message after a successful 3-in-a-row.
5. Use **Reset** or **New Game** buttons to start over.

---

## Technologies Used

- HTML5 (for the game structure)
- CSS3 (for styling and layout)
- JavaScript (for game logic and interactivity)

---

## Future Improvements

- Add AI for single player mode.
- Improve UI/UX with animations and better styling.
- Add score tracking for multiple rounds.
- Display whose turn it is.

---

Feel free to fork, improve, or suggest features!

