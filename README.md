# Treasure-Hunt game
Report: Treasure Hunt in the Enchanted Forest
 Optimization details
 To find the optimal path with minimal cost using the provided code, several
 optimization strategies have been employed:
 1. Uniform Cost Search (UCS):
 ● UCSalgorithm explores the search space in a breadth-first manner,
 prioritizing nodes with lower path costs.
 ● Priority queue (heapq) is used to maintain the frontier, ensuring that
 nodes with lower path costs are explored first.
 ● Thealgorithm terminates when the goal node is reached, ensuring
 that the shortest path from the start node to the goal node is found.
 2. Heuristic Function (A* Search):
 ● A*search algorithm utilizes the Manhattan distance heuristic to guide
 the search towards the goal node efficiently.
 ● Theheuristic function estimates the cost of reaching the goal node
 from a given node, helping prioritize nodes that are closer to the goal.
 ● Bycombining the heuristic estimate with the actual path cost, A*
 search explores promising paths first, leading to faster convergence
 towards the optimal solution.
 3. Randomized Grid Generation:
 ● Thegrid is randomly generated with obstacles, endpoints, and animal
 encounter probabilities, ensuring diverse and unpredictable search
 scenarios.
 ● Randomized grid generation introduces variability in the search
 space, encouraging the algorithm to adapt to different environments
 and find robust solutions.
4. Efficient Data Structures and Algorithms:
 ● Theuseof sets for tracking visited nodes and a priority queue for
 managing the frontier ensures efficient memory utilization and
 traversal of the search space.
 ● Byemploying heapq module for maintaining the priority queue, the
 algorithm achieves optimal time complexity for inserting and retrieving
 elements.
 5. Adaptive Animal Encounter Simulation:
 ● Thefunction to simulate animal encounters incorporates a probability
 distribution to model the likelihood of encountering animals along the
 path.
 ● Randomized animal encounter probabilities add realism to the search
 environment, challenging the algorithm to navigate unpredictable
 terrain conditions.
 6. Dynamic Cost Assignment:
 ● Thecost function assigns dynamic costs to grid elements based on
 their type (safe grid, obstacle, endpoint) and the occurrence of animal
 encounters.
 ● Byincorporating random cost ranges for each grid element, the
 algorithm adapts to varying path conditions, optimizing for both safety
 and efficiency.
 7. Comprehensive Path Visualization:
 ● Thecode includes functions to display the grid, visualize the optimal
 path, and trace animal actions along the path, facilitating
 comprehensive analysis and interpretation of the results.
