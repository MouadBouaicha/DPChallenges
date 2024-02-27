# Dynamic Programming Problems

This repository contains solutions to various dynamic programming problems. Each problem focuses on a different type of challenge within the domain of dynamic programming.

## Types of Problems in Dynamic Programming:

- **Decision Problem:** `canSum`
- **Combinatoric Problem:** `howSum`
- **Optimization Problem:** `bestSum`

## Problem 1: Fibonacci Sequence

Write a function `fib(n)` that takes in a number as an argument. The function should return the n-th number of the Fibonacci sequence.

- The 1st and 2nd number of the sequence is 1.
- To generate the next number of the sequence, we sum the previous two.

## Problem 2: Grid Traveler

Imagine you are a traveler on a 2D grid. You begin in the top-left corner and your goal is to travel to the bottom-right corner. You may only move down or right.

- In how many ways can you travel to the goal on a grid with dimensions m * n?
- Write a function `gridTraveler(m, n)` that calculates this.

## Problem 3: Can Sum

Write a function `canSum(targetSum, numbers)` that takes in a targetSum and an array of numbers as arguments.

- The function should return a boolean indicating whether it is possible to generate the targetSum using numbers from the array.
- You may use an element of the array as many times as needed.
- All input numbers are nonnegative.

## Problem 4: How Sum

Write a function `howSum(targetSum, numbers)` that takes in a targetSum and an array of numbers as arguments.

- The function should return an array containing any combination of elements that add up to exactly the targetSum.
- If there is no combination that adds up to the targetSum, then return null.
- If there are multiple combinations possible, you may return any single one.

## Problem 5: Best Sum

Write a function `bestSum(targetSum, numbers)` that takes in a targetSum and an array of numbers as arguments.

- The function should return an array containing the shortest combination of numbers that add up to exactly the targetSum.
- If there is a tie for the shortest combination, you may return any one of the shortest.

## Problem 6: Can Construct

Write a function `canConstruct(target, wordBank)` that accepts a target string and an array of strings.

- The function should return a boolean indicating whether the `target` can be constructed by concatenating elements of the `wordBank` array.
- You may reuse elements of `wordBank` as many times as needed.

## Problem 7: Count Construct

Write a function `countConstruct(target, wordBank)` that accepts a target string and an array of strings.

- The function should return the number of ways that the `target` can be constructed by concatenating elements of the `wordBank` array.
- You may reuse elements of `wordBank` as many times as needed.

## Problem 8: All Construct

Write a function `allConstruct(target, wordBank)` that accepts a target string and an array of strings.

- The function should return a 2D array containing all of the ways that the target can be constructed by concatenating elements of the `wordBank` array.
- Each element of the 2D array should represent one combination that constructs the `target`.
- You may reuse elements of `wordBank` as many times as needed.

## Time and Space Complexities

### Fibonacci Sequence

- Brute force: O(2^n) time, O(n) space
- Memoized: O(n) time, O(n) space

### Grid Traveler

- Brute force: O(2^(n+m)) time, O(n + m) space
- Memoized: O(m * n) time, O(n + m) space

### CanSum

- Brute force: O(n^m * m) time, O(m) space
- Memoized: O(n*m^2) time, O(m) space

### BestSum

- Brute force: O(n^m * m) time, O(m^2) space
- Memoized: O(n*m^2) time, O(m^2) space

## Memoization Recipe

1. Make it work.
   - Visualize the problem as a tree.
   - Implement the tree using recursion.
   - Test it.
2. Make it efficient.
   - Add a memo object.
   - Add a base case to return memo values.
   - Store return values into the memo.

## Tabulation Recipe

- Visualize the problem as a table.
- Size the table based on the inputs.
- Initialize the table with default values.
- Seed the trivial answer into the table.
- Iterate through the table.
- Fill further positions based on
"# DPChallenges" 
"# DPChallenges" 
"# DPChallenges" 
"# DPChallenges" 
