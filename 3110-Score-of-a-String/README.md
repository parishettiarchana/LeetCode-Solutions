# 3110. Score of a String

## Problem
https://leetcode.com/problems/score-of-a-string/

Difficulty: Easy

## Approach
* Initialize a variable `ans` to store the total score.
* Traverse the string from the first character to the second-last character.
* For each pair of adjacent characters, calculate the absolute difference between their ASCII values using the `ord()` function.
* Add the difference to `ans`.
* Return the final score after processing all adjacent character pairs.

## Time Complexity
- O(n)
  - n = length of the string

## Space Complexity
- O(1)

## Solution

[Python Solution](solution.py)