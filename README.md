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

### Implementation

The implementation of the project follows these main steps:

1. **Maze Generation**: The maze layout is predefined as a 2D array in the `Main` class. Alternatively, you can implement maze generation algorithms such as recursive backtracking or Prim's algorithm to generate random mazes.

2. **Depth-First Search (DFS)**: The DFS algorithm is implemented in the `Game` class to find a path from the starting point to the exit in the maze. It explores the maze recursively, moving through each available path until it reaches the exit or explores all possible paths.

3. **Game Logic**: The `Game` class manages the game logic, including handling user input for player movement and updating the display to show the maze with the player's position.

### Analysis/Evaluation

#### Performance:
- The DFS algorithm provides a simple and efficient way to find a path through the maze. However, its performance may degrade on larger mazes or mazes with complex layouts.
- For larger mazes or more complex scenarios, alternative pathfinding algorithms such as A* (A-star) or Dijkstra's algorithm may offer better performance.

#### Scalability:
- The project is designed to handle small to medium-sized mazes. 
- To support larger mazes or additional features, such as multiple players or dynamic maze generation, the codebase may require refactoring and optimization.

### Conclusion

The maze game project demonstrates the implementation of a simple game with integrated pathfinding using the DFS algorithm. While the project provides a basic foundation for maze navigation, there is room for further enhancements and optimizations to improve performance, scalability, and user experience. Future iterations could include features such as interactive gameplay, support for larger mazes, additional pathfinding algorithms, and customizable maze generation.

### Note

This version of the maze game does not support interactive gameplay. If we want to implement interactive controls where the player can navigate the maze in real-time, additional modifications will be required.
