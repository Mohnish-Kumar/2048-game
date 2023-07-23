# 2048 Game

This is a simple implementation of the popular 2048 game using the Tkinter library in Python.

## How to Play

1. Run the script using a Python interpreter.

2. The game window will open with a 4x4 grid.

3. Use the following keyboard keys to move the tiles:

   - W: Move Up
   - S: Move Down
   - A: Move Left
   - D: Move Right

4. The goal of the game is to combine tiles with the same value to reach the 2048 tile.

5. When two tiles with the same value collide, they merge into one tile with twice the value.

6. Continue merging tiles and strategize to achieve the 2048 tile.

7. If the grid fills up, and no more valid moves can be made, the game is over.

8. The game will show "You Win!" if you reach the 2048 tile and "You Lose!" if the grid fills up.

## Game Controls

- W: Move tiles up
- S: Move tiles down
- A: Move tiles left
- D: Move tiles right

## Game Logic

The game uses the following logic:

- The initial grid contains two randomly placed "2" tiles.
- Pressing the appropriate keys moves the tiles in the corresponding direction.
- Tiles with the same value merge when they collide, forming a new tile with twice the value.
- After each move, a new "2" tile is added to an empty cell randomly.

## Note

This implementation is a basic version of the 2048 game and is meant to demonstrate how the game can be created using Python and Tkinter. It does not include advanced features or high scores.

Enjoy playing 2048! 🎮
