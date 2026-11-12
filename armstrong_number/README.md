# Armstrong Number Check

## Problem Statement
An Armstrong (narcissistic) number equals the sum of its own digits each raised to the power of the number of digits. Given a number, check if it is an Armstrong number.

> Example: 153 = 1³ + 5³ + 3³ = 1 + 125 + 27 = **153** ✅

## Examples

| Input | Calculation | Output |
|-------|-------------|--------|
| `153` | 1³+5³+3³ = 153 | `true` |
| `370` | 3³+7³+0³ = 370 | `true` |
| `371` | 3³+7³+1³ = 371 | `true` |
| `9474` | 9⁴+4⁴+7⁴+4⁴ = 9474 | `true` |
| `123` | 1³+2³+3³ = 36 ≠ 123 | `false` |
| `100` | 1³+0³+0³ = 1 ≠ 100 | `false` |
