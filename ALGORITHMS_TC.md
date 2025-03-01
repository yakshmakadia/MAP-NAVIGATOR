# Shortest Path Algorithms

## Dijkstra's Algorithm
- Systematically calculates the shortest path between nodes in a graph.
- Time Complexity: O(V²) or O((V + E) * log(V)) with a priority queue.

## A* Algorithm
- Uses heuristic functions to improve search efficiency.
- Faster than Dijkstra’s in many cases due to heuristic guidance.
- Best for pathfinding in large graphs.

# Time Complexity Analysis

## Best Case
- If the path is direct, complexity approaches O(V).

## Worst Case
- If all nodes and edges must be explored, complexity is O(V²).

## Average Case
- For Dijkstra’s with a binary heap: O((V + E) * log(V)).
- For A*: Similar complexity but often faster due to heuristics.
  
## Comparison
| Algorithm   | Time Complexity | Best Use Case |
|------------|----------------|--------------|
| Dijkstra   | O((V + E) * log(V)) | General shortest path |
| A*         | O((V + E) * log(V)) | Large graphs with informed heuristics |


