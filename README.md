I can help you write a `README.md` file for your project based on the content of the notebook you uploaded. Let me first analyze the file, and then I will create a suitable `README.md` for it.

Based on the content of your Jupyter notebook, which focuses on Classical AI, drone navigation, and pathfinding, here's a draft for your `README.md` file:

---

# Assignment 2 - Classical AI

**Student Name:** Duong Phu Dong  
**Student ID:** s3836528  

## Overview

This project is part of the **Foundations of Artificial Intelligence for STEM** course and focuses on implementing classical AI techniques for drone navigation in a 2D city map. The notebook demonstrates how to use different algorithms and heuristics to find optimal paths for delivery drones.

## Project Structure

The project is implemented in a Jupyter Notebook and contains the following sections:

1. **Map Demonstration:**
   - The city map is represented as a 2D grid where each cell corresponds to an empty space or an obstacle. The starting position of the drone and the delivery destinations are stored in variables `starting_location` and `delivery_locations`, respectively.

2. **Heuristic Functions:**
   - The project uses heuristic functions like the Manhattan distance to estimate the cost of moving from one location to another on a grid. The heuristic function is implemented as:
     ```python
     def heuristicManhattan(current_location, goal):
         result = abs(goal[0] - current_location[0]) + abs(goal[1] - current_location[1])
         return result
     ```

3. **A* Algorithm Implementation:**
   - The notebook contains an implementation of the A* algorithm, which is used to find the shortest path from the starting location to the delivery destinations.

4. **Pathfinding Demonstration:**
   - The final section demonstrates how the drone navigates through the city using the A* algorithm, avoiding obstacles and reaching its destinations.

## How to Run

1. Clone the repository to your local machine:
   ```bash
   git clone <repository_url>
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Assignment2_OptionA_s3836528.ipynb
   ```
3. Execute the cells to see the map demonstration and pathfinding in action.

## Requirements

- Python 3.x
- Jupyter Notebook
- `numpy` (if required for additional functionalities)

Install the required packages using:
```bash
pip install -r requirements.txt
```

## Acknowledgments

This assignment is a part of the Foundations of Artificial Intelligence for STEM coursework and explores classical AI techniques for pathfinding.
