# CS31CodingProject

## Problem 1
The algorithm to solve the number guessing game employs dynamic programming. The main idea behind the algorithm is that the number Alice picks on either end of the array is based on her maximum weight of the resulting sub array of her pick. Given that each choice Alice makes is based on a smaller subset of the same problem, dynamic programming makes sense as a solution to this problem. The base case of this problem is a two number array where Alice gets to pick the larger of the two numbers. The maximum min weight is then the maximum weight Alice can achieve assuming Bob makes the best moves. This is the max min weight beacuse even if Bob makes a bad move, Alice will always achieve that baseline.
