# Find the Missing Number in a Sequential Array

## Problem Statement
Given an array containing `n` distinct numbers taken from the range `0` to `n`, find the one number that is missing from the sequence.

## Examples

| Input | Expected Range | Output |
|-------|---------------|--------|
| `[3, 0, 1]` | 0 to 3 | `2` |
| `[0, 1]` | 0 to 2 | `2` |
| `[9, 6, 4, 2, 3, 5, 7, 0, 1]` | 0 to 9 | `8` |
| `[0]` | 0 to 1 | `1` |

> **Hint:** Use the formula `Sum = n*(n+1)/2` and subtract the actual sum.
