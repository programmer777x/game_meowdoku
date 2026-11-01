# 🐾 Meowdoku

A cozy, cat-themed logic puzzle game inspired by Sudoku, built with vanilla HTML, CSS, and JavaScript. 

**Play the live game here:** [https://programmer777x.github.io/game_meowdoku/](https://programmer777x.github.io/game_meowdoku/)

## 🎮 How to Play

The goal is to place exactly one cat in every row, every column, and every colored region on the board.

**The Rules:**
* 🐱 **One per row:** No two cats can share the same row.
* 🐱 **One per column:** No two cats can share the same column.
* 🐱 **One per color:** No two cats can share the same colored region.
* 🚫 **No touching:** Cats cannot touch each other, not even diagonally!

**Controls:**
* **Tap / Click** a cell to cycle through: Empty → Note (✕) → Cat (🐱) → Empty.
* **Right-click** (or long-press on mobile) to instantly clear a note or cat.
* **Hint** will glow the cell of an unsolved cat.
* **Lives:** You start with 3 lives (hearts). Placing a cat that breaks a rule costs a life and briefly shows you exactly why. You can tap the lives to change the icon style!

## 🛠️ Tech Stack & Features
* **No dependencies:** Just pure HTML, CSS, and JavaScript in a single `index.html` file.
* **Procedural Generation:** Puzzles are generated on the fly using a backtracking algorithm and region-growing.
* **Difficulty Solver:** Features a built-in logic-only solver that classifies generated boards into Easy, Medium, or Hard based on the deduction techniques required to solve them.
* **Mobile Friendly:** Designed to work beautifully on phone screens and can be added to your iOS Home Screen as a web app. 

## 🚀 Running Locally

Because everything is contained in one file, there's no build step. 
1. Clone this repository.
2. Open `index.html` in any web browser.

## 🎨 Assets
The app uses standard emojis for the cats (🐱) and lives (❤️/🐟). The home screen icon is served via `apple-touch-icon.png` in the root directory.
