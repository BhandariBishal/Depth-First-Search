# Depth-First-Search
# Depth-First Search (DFS) Implementation

A Python implementation of Depth-First Search algorithm using both recursive and iterative approaches.

## Features
- Recursive DFS implementation
- Iterative DFS implementation using a stack
- Example usage with a sample graph

## Usage

# Define your graph as an adjacency list
graph = {
    'A': ['B', 'C'],
    'B': ['A', 'D', 'E'],
    'C': ['A', 'F'],
    'D': ['B'],
    'E': ['B', 'F'],
    'F': ['C', 'E']
}

# For recursive DFS
result = dfs_recursive(graph, 'A')

# For iterative DFS
result = dfs_iterative(graph, 'A')

#Output
The code provides two different implementations of DFS, allowing users to choose between recursive and iterative approaches based on their needs.
