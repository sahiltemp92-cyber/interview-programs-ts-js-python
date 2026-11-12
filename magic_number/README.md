# Magic Number Check

## Problem Statement
A number is a **magic number** if the repeated sum of its digits eventually equals `1`.

> Example: 19 → 1+9=10 → 1+0=**1** ✅

## Examples

| Input | Steps | Output |
|-------|-------|--------|
| `19` | 1+9=10 → 1+0=1 | `true` |
| `1` | Already 1 | `true` |
| `10` | 1+0=1 | `true` |
| `55` | 5+5=10 → 1+0=1 | `true` |
| `123` | 1+2+3=6 | `false` |
| `29` | 2+9=11 → 1+1=2 | `false` |
