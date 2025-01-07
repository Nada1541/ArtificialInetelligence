# AI Project: Grid-Based Pathfinding and Reinforcement Learning

## Overview
This project focuses on implementing and analyzing various AI search algorithms and reinforcement learning techniques to solve a grid-based pathfinding problem. The problem involves navigating a robot from a start point to a goal point on a grid while avoiding obstacles.

The project is divided into two phases:
- **Phase 1**
- **Phase 2**

---

## **Phase 1: Classical Search Algorithms**

### Objective
Implementing and comparing various search algorithms to find the optimal path from the initial state to the goal state in a grid environment.

### Algorithms Implemented
1. **Greedy Best-First Search (GBFS)**
   - Manhattan and Euclidean heuristics.
2. **A-Star Search**
   - Manhattan and Euclidean heuristics.
3. **Simulated Annealing (SA)**
4. **Depth-First Search (DFS)**
5. **Iterative Deepening Search (IDS)**
6. **Breadth-First Search (BFS)** (Tree and Graph variants)
7. **Uniform Cost Search (UCS)**
8. **Hill Climbing**
9. **Genetic Algorithm**

### Grid Representation
- `A`: Agent's current position.
- `G`: Goal position.
- `X`: Obstacles.
- `.`: Free cells.

### Performance Metrics
- Solution Path
- Cost (Path length or energy cost)
- Execution Time
- Max Frontier Size

### Visualization
- Grid visualization for each algorithm.
- State transitions are displayed at each step for better understanding.

---

## **Phase 2: Reinforcement Learning with Q-Learning**

### Objective
Implementing a Q-Learning agent to learn an optimal policy for navigating the grid from the initial state to the goal state.

### Key Features
- **Reward System:**
   - Goal State: +100
   - Step Cost: -1
   - Obstacle Penalty: -100
- **Q-Learning Parameters:**
   - Learning Rate (α): 0.01
   - Discount Factor (γ): 0.99
   - Exploration Rate (ε): Adaptive
- **Exploration Function:** Ensures a balance between exploration and exploitation.

### Visualization
1. **Q-Values Table:** State-action Q-values displayed.
2. **Optimal Policy Grid:** Visual representation of the learned policy.
   - `^`: Move Up
   - `v`: Move Down
   - `<`: Move Left
   - `>`: Move Right
3. **State Utilities:** Final utility values for each grid state.
4. **Agent Path:** Path taken by the agent during training.
