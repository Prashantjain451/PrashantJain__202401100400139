# PrashantJain__202401100400139
Approach to Solve the 8-Puzzle Problem
1️⃣ Understanding the Problem
The 8-Puzzle consists of a 3×3 grid containing 8 numbered tiles and one empty space (0). The goal is to move tiles by sliding them into the empty space to reach the goal state:

Copy
Edit
1 2 3  
4 5 6  
7 8 0  
We need to find the shortest sequence of moves that leads to this goal.

2️⃣ Choosing the Right Algorithm
Since this is a state-space search problem, we use the A (A-star) Search Algorithm* because:
✅ It guarantees finding the shortest path (optimal solution).
✅ It efficiently explores only relevant moves, reducing computation time.

 Summary of the Approach
✅ A Search Algorithm* is used for optimal pathfinding.
✅ Manhattan Distance Heuristic estimates the best path.
✅ Priority Queue (Min-Heap) ensures the best move is always expanded first.
✅ Visited states are tracked to avoid redundant calculations.
✅ Backtracking is used to reconstruct the solution path.
 Key Concepts in the Code
✅ A Search Algorithm:* Finds the optimal path efficiently.
✅ Manhattan Distance Heuristic: Helps estimate the best moves.
✅ Priority Queue (Heap): Always expands the most promising state first.
✅ State Tracking: Avoids revisiting the same state.

