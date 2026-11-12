# Sort an ArrayList Using Comparable and Comparator

## Problem Statement
Given a list of custom objects (e.g., `Student` with `name` and `age`), sort the list in two ways:
1. **Comparable** — natural ordering by age
2. **Comparator** — custom ordering by name alphabetically

## Example

**Input:**
```
[Student("Charlie", 22), Student("Alice", 20), Student("Bob", 25)]
```

**Sorted by age (Comparable):**
```
[Alice(20), Charlie(22), Bob(25)]
```

**Sorted by name (Comparator):**
```
[Alice(20), Bob(25), Charlie(22)]
```
