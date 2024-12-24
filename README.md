# Pipemania AI Solver

An AI-based solver for the classic puzzle game **Pipemania**, developed in Python. This project demonstrates the use of algorithmic logic to calculate optimal pipe connections. 

## Features
- **AI Logic Implementation**:
  - Algorithms to compute the optimal moves for connecting pipe pieces on a grid.
  - State and action management for different types of pipe pieces.
- **Puzzle Representation**:
  - Internal board representation for dynamic puzzle solving.
  - Modular design for handling various pipe configurations.
- **Efficient Search**:
  - Utilized search algorithms such as A* to find the optimal solution. (even though I tried other algorithms but A* worked the best)

## My Contributions
1. Developed:
   - Core logic for **piece state transitions**.
   - Functions to calculate **possible moves** and **connections** between pipe pieces.
2. Enhanced the AI Solver with:
   - **Heuristic function** for the A* search algorithm.
   - Methods for goal testing and state expansion.
3. Debugged and validated the solver using provided test cases.

## Provided Materials
- Base code for input parsing and puzzle visualization.
- Test cases for debugging and validation.

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - `sys` for input handling.
  - `copy` for deep state cloning.
  - `time` for execution timing.

## How It Works
1. **Input**: A grid-based puzzle configuration representing different pipe pieces.
2. **Processing**:
   - AI computes the optimal actions to connect pipes.
   - Utilizes a search algorithm to minimize the number of moves.
3. **Output**: Solved puzzle printed in a human-readable format.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/mehakkhosa/pipemania-ai-solver.git
   cd pipemania-ai-solver

  
