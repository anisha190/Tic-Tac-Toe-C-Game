# Tic-Tac-Toe Game (C Language)

A classic 2-player terminal-based Tic-Tac-Toe game written in C. The application features an interactive 3x3 grid display, turn-based input for players 'X' and 'O', input validation, and dynamic win/tie detection.

## 🎮 How to Play

1. **Grid Setup**: The board is represented as a 3x3 grid indexed from row `0` to `2` and column `0` to `2`.
2. **Taking Turns**: Players alternate turns entering row and column coordinates[cite: 1].
3. **Move Validation**: The program ensures coordinates are within bounds (`0-2`) and prevents overwriting occupied slots[cite: 1].
4. **Winning/Tie**: The game checks all rows, columns, and diagonals after every turn and declares a winner or a tie if all 9 turns are exhausted[cite: 1].

## 🚀 How to Run

### 1. Compile using GCC:
```bash
gcc "tic tac toe main.c" -o tictactoe
