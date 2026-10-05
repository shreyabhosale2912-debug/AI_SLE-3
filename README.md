# SLE-3: Architectural Design using Full C4 Model

## Student Details

- **Name:** Shreya Bhosale
- **PRN:** 25UAM140
- **Course:** 02AML204 – Introduction to Artificial Intelligence
- **System:** BFS/DFS Maze Search System

## About the Project

This project presents the architectural design of a Maze Search System using the Full C4 Model.

The system is based on the BFS and DFS search algorithms used in the previous SLE-2 work. The architecture is represented at four levels:

1. **Context** – Shows the overall system and its interaction with the user.
2. **Container** – Shows the major modules of the system.
3. **Component** – Shows the internal components of the Search Engine.
4. **Code** – Shows the main functions used to implement the search system.

## C4 Architecture

### Level 1 – Context Diagram

The user provides the maze and search information to the Maze Search System. The system processes the input and provides the search result or path.

### Level 2 – Container Diagram

The major containers are:

- **Input Module** – Receives the maze and required input.
- **Search Engine** – Executes BFS or DFS.
- **Memory / Visited Set** – Keeps track of visited positions.
- **Output Module** – Displays the final search result or path.

### Level 3 – Component Diagram

The Search Engine contains smaller components:

- **Frontier** – Stores nodes waiting to be explored.
- **Explored Set** – Stores already visited nodes.
- **Goal Test** – Checks whether the goal has been reached.
- **Path Reconstructor** – Reconstructs the path from start to goal.

### Level 4 – Code Level

The important functions of the system include:

- `bfs()` – Performs Breadth-First Search.
- `dfs()` – Performs Depth-First Search.
- `get_neighbors()` – Finds valid neighboring positions.
- Path reconstruction – Builds the final path.

## Connection with SLE-2

SLE-2 focused on the performance analysis and comparison of BFS and DFS for the Maze Search System.

SLE-3 continues the same system and focuses on its complete software architecture using the C4 Model.

## AI Contribution

AI tools were used as a supporting resource for understanding the C4 Model, organizing the architecture, and improving explanations. The final system architecture and report were reviewed and understood by the student.

## Learning Outcome

This SLE helped in understanding how a search-based AI system can be represented from a high-level system view down to its main code-level functions.

## GitHub

[GitHub Repository](https://github.com/shreyabhosale2912-debug/AI_SLE-3)
