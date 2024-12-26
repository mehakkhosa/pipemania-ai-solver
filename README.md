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
  - Utilized search algorithms such as A* to find the optimal solution. (I tried other algorithms but A* worked the best)

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
4. A* was chosen because of its ability to efficiently find the shortest path by combining cost-so-far and heuristic estimations, making it ideal for this puzzle format.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/mehakkhosa/pipemania-ai-solver.git
   cd pipemania-ai-solver

## Usage

![image](https://github.com/user-attachments/assets/06640f71-bc69-4413-8ccb-68f02168d5fb)

Example input:

![image](https://github.com/user-attachments/assets/bfa6d9b6-7b9e-4fe0-a5c1-22a1f81fcd6c)

The AI solver computes the optimal connections and outputs the following result:

![image](https://github.com/user-attachments/assets/c5988897-ed67-479d-87d7-884a052e6414)

## Acknowledgments
This project was developed as part of an academic exercise at **Instituto Superior Técnico (IST)**. Base code and test cases were provided by the course instructors.








