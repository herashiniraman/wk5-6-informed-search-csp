# NOTES

## A* Heuristic
The heuristic used in A* search is Manhattan distance, calculated as the absolute difference between the row and column positions of the current node and the goal node.It is admissible because it never overestimates the true shortest path cost when movement is limited to four directions.The heuristic only estimates the minimum number of horizontal and vertical moves required to reach the goal.


## Test Case Design
The A* test cases cover different categories from the mind-map: a normal obstacle path case, an edge/boundary case, and an unsolvable case where no valid path exists. The CSP test cases cover a normal solvable colouring problem, a constraint checking case, and an over-constrained case where a solution is impossible. These tests were chosen to demonstrate different behaviours instead of repeating similar successful cases.


