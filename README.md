# Quiz2-Design-Analysis-of-Algorithms-D

## Maze Game with Depth-First Search (DFS) Implementation

This project is a simple maze game implemented in Java with an integrated Depth-First Search (DFS) algorithm to find a path through the maze.

### Description

The project consists of the following components:

- **Maze**: Represents the maze structure. It contains information about the maze layout, the starting point, and the exit point.
- **Player**: Represents the player within the maze. It keeps track of the player's current position.
- **Game**: Manages the game logic, including the DFS algorithm to find a path from the starting point to the exit.
- **Main**: Entry point of the application.

### Depth-First Search (DFS) Algorithm

The DFS algorithm is used to find a path from the starting point to the exit in the maze. It explores the maze recursively, moving through each available path until it reaches the exit or explores all possible paths. The DFS implementation provided here is a basic version that does not involve interactive gameplay. Instead, it automatically searches for a path and prints the maze with the player's position as it explores.

### How to Play

1. **Setup the Maze Layout**:
   Define the maze layout in the `Main` class. The maze is represented as a 2D array where:
   - `0` represents an open path.
   - `1` represents a wall.

2. **Define the Start and Exit Points**:
   Specify the starting position (`startRow`, `startCol`) and the exit position (`exitRow`, `exitCol`) in the maze.

3. **Run the Program**:
   Execute the program. The DFS algorithm will automatically search for a path from the start position to the exit. It will print the maze with the player's current position as it explores.

4. **Output**:
   The output will display the maze with the player's position represented by `P` and the exit by `E`. If a path is found, it will print "Path found:"; otherwise, it will print "No path found."

### Note

This version of the maze game does not support interactive gameplay. If you're interested in implementing interactive controls where the player can navigate the maze in real-time, additional modifications will be required.
