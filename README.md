
# MAP NAVIGATOR

## Overview
Map Navigator is an advanced route optimization system designed to overcome inefficiencies in existing navigation solutions. It utilizes Dijkstra's and A* algorithms to determine the shortest path between two points while integrating real-time traffic updates and accessibility features.

## Problem Statement
Existing map navigation systems suffer from inefficiencies, outdated data, and lack of real-time traffic updates, leading to unreliable routing and poor user experiences. Additionally, inadequate integration of transportation modes and limited accessibility support create further challenges. This project aims to address these issues by developing an optimized and efficient map navigation solution.

## Features
- Implements **Dijkstra's Algorithm** for shortest path calculation.
- Uses **A* Algorithm** for efficient pathfinding with heuristic guidance.
- Handles user-defined start and end markers on the map.
- Provides a visualized shortest route.
- Supports real-time traffic simulation.
- Offers an optimized system for travel planning and execution.

## Algorithms Used
### 1. **Dijkstra's Algorithm**
- Finds the shortest path between nodes in a graph.
- Guarantees the shortest route in weighted graphs.
- Time Complexity: **O((V + E) * log(V))** (with a priority queue implementation).

### 2. **A* Algorithm**
- Uses a heuristic function to prioritize node expansion.
- More efficient than Dijkstra’s in large search spaces.
- Time Complexity: **O((V + E) * log(V))**, depending on heuristic efficiency.

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/map-navigator.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt  # If using Python
   ```
3. Run the application:
   ```bash
   python main.py
   ```
   or open the HTML file if it's a web-based implementation.

## License
This project is open-source and available under the MIT License.


