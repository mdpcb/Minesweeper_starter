# Minesweeper Game Assignment

## Objective
Write a simple console-based Minesweeper game in Java. The game should generate a grid with randomly placed mines, allow players to uncover cells, and display nearby mine counts.

## Requirements

1. **Grid Setup**:
   - Create a 10x10 grid using a 2D array.
   - Randomly place a set number of mines (e.g., 10 mines).
   - Each cell in the grid should either contain a mine or show the number of adjacent mines when revealed.

2. **Game Mechanics**:
   - Prompt the player to enter coordinates to reveal a cell.
   - If the player reveals a cell with a mine, they lose, and the game ends.
   - If they reveal a cell without a mine, display the number of adjacent mines.
   - If the player uncovers all non-mine cells, they win, and the game should display a victory message.

3. **Basic Display**:
   - Use Unicode or ASCII characters to display the grid, with unrevealed cells, revealed cells, and mines distinguishable by symbols.
   - For example, use `#` for unrevealed cells, `X` for mines, and numbers for revealed cells with adjacent mines.

## Extra Credit
- **Flagging Mines**: Allow players to flag cells they suspect contain mines. Use a separate symbol (e.g., `F`) for flagged cells, and track flagged cells throughout the game.

## Example of Basic Gameplay

```plaintext
Minesweeper Board:
    0 1 2 3 4 5 6 7 8 9 
0  # # # # # # # # # #
1  # # # # # # # # # #
2  # # # # # # # # # #
3  # # # # # # # # # #
4  # # # # # # # # # #
5  # # # # # # # # # #
6  # # # # # # # # # #
7  # # # # # # # # # #
8  # # # # # # # # # #
9  # # # # # # # # # #

Enter command (e.g., "reveal 3 4"): 
```
