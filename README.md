# Rock Paper Scissors Game

A browser-based Rock Paper Scissors game built from scratch using **HTML**, **CSS**, and **JavaScript** — developed as part of the [Brainnest Frontend Development Industry Training](https://brainnest.consulting) (February–March 2023).

---

## Preview

A clean, warm-styled game with a yellow background (`#F4D05E`) and styled buttons. The player competes against the computer — first to 5 wins takes the game.

---

## Features

- 🪨 Rock, 📄 Paper, ✂️ Scissors — all three choices available as buttons
- **Score tracking** — player score and computer score update after every round
- **Win condition** — first to reach 5 points wins the game
- **Buttons automatically disabled** when the game ends — no more clicks after a winner is decided
- **Random computer selection** using `Math.random()`
- Result message displayed after every round ("You win!", "You lose!", "It's a tie!")

---

## Technologies Used

| Technology | Purpose |
|------------|---------|
| HTML5 | Structure, buttons, result display |
| CSS3 + Flexbox | Styling and layout |
| JavaScript (Vanilla) | Game logic, score tracking, DOM updates |

---

## How It Works

The game is built around one main function:

- **`playRound(playerSelection)`** — takes the player's choice, generates a random computer choice, compares them using game logic, updates the score, and displays the result.

Two helper elements:
- **`disableButtons()`** — disables all three buttons once a player reaches 5 points, preventing further input after the game ends.
- **Event listeners** on each button pass the player's choice directly to `playRound()`.

---

## Game Logic

```
Rock beats Scissors
Paper beats Rock
Scissors beats Paper
Same choice = Tie
First to 5 points wins
```

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Abdu-fix/JavaScript-Calculator.git
   ```
2. Open `index.html` in your browser — no installation needed.

---

## What I Learned

- Writing **conditional logic** with multiple `if/else` conditions
- Using **`Math.random()`** to generate random computer decisions
- **Tracking state** across multiple rounds with score variables
- **Disabling DOM elements** programmatically based on game conditions
- Building a complete mini-game with a clear win condition

---

## Author

**Abdelwahid Abdelmahmoud**  
GitHub: [@Abdu-fix](https://github.com/Abdu-fix)
