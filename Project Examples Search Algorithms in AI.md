8-Puzzle Solver Using A* Search Algorithm
1. Introduction

Search algorithms are a fundamental part of Artificial Intelligence, especially in solving state-space problems where multiple paths may lead to a goal. One of the most common benchmark problems used to demonstrate the efficiency of search algorithms is the 8-Puzzle problem.
This project presents an interactive implementation of the 8-Puzzle problem solved using the A* search algorithm, combined with a modern web-based visualization to help users understand how the algorithm works step by step.

2. Problem Description

The 8-Puzzle problem consists of a 3×3 grid containing eight numbered tiles and one empty space. The objective is to reach a predefined goal configuration by sliding tiles into the empty space, while following valid movement rules (up, down, left, right).
The challenge lies in finding the optimal solution path with the minimum number of moves while efficiently exploring the search space.

3. Project Objectives

The main objectives of this project are:

To implement the A* search algorithm for solving the 8-Puzzle problem.

To use an admissible heuristic (Manhattan Distance) to guarantee an optimal solution.

To visualize the puzzle states and solution path step by step.

To analyze algorithm performance using metrics such as:

Number of explored nodes

Solution path length

To provide an educational and interactive tool for understanding informed search algorithms.

4. Methodology

The project models the puzzle as a state-space search problem:

State Representation:
Each puzzle state is represented as an array of 9 elements, where 0 represents the empty tile.

Initial State:
A randomly shuffled but solvable puzzle configuration.

Goal State:
[1, 2, 3, 4, 5, 6, 7, 8, 0]

Actions:
Moving the empty tile up, down, left, or right.

Cost Function (g(n)):
Each move has a uniform cost of 1.

Heuristic Function (h(n)):
Manhattan Distance, which estimates how far each tile is from its goal position.

Evaluation Function:
f(n) = g(n) + h(n)

The algorithm also includes a solvability check to ensure that only valid puzzle configurations are processed.

5. Tools and Technologies

Programming Language: JavaScript

Framework: React (with Hooks)

Styling: Tailwind CSS

Algorithm: A* Search Algorithm

Environment: Web-based (runs directly in the browser)

6. Expected Outcomes

By the end of this project:

The system will successfully solve any solvable 8-Puzzle configuration.

Users will be able to:

Shuffle the puzzle

Solve it using A*

Navigate through the solution step by step

The project will clearly demonstrate the efficiency of informed search compared to uninformed approaches.

Performance statistics will provide insight into how A* reduces the number of explored states.

7. Significance of the Project

This project serves both educational and practical purposes:

Helps students understand A* search and heuristic functions.

Demonstrates how AI algorithms can be visualized interactively.

Bridges the gap between theoretical AI concepts and real-world implementation.

8. Conclusion

The 8-Puzzle Solver project showcases the power of the A* search algorithm in solving complex search problems optimally. By combining algorithmic correctness with a modern user interface, the project provides an effective learning tool for Artificial Intelligence and search algorithms.