# Billiard Game in Squeak Smalltalk
Max Mullokandov - 205647555
Explanation for Assignment 15
How to Play Billiard Game:

1. Game Objective:
- Get all numbered balls (1-15) into the pockets
- Click with the left mouse button (default mouse settings) - the white ball serves as the cue ball
- Type in the workspace to run the game:
| table |
table := BilliardTableMorph new openInWorld.


2. How to Play:
- Click on the white ball with the mouse
- Drag the mouse to aim the shot
- Release the mouse to execute the shot
- The further you drag, the stronger the shot will be

3. Basic Rules:
- If the white ball goes into a pocket, it will automatically respawn
- The game ends when all numbered balls are in pockets
- The game will automatically reset when all balls are in pockets

4. Tips:
- Try to plan your shot in advance
- Use the table edges for indirect shots
- Control the shot power according to the dragging distance
