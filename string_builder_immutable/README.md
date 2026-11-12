# Immutable Strings vs StringBuilder

## Problem Statement
Demonstrate the concept of **String immutability** vs **StringBuilder mutability**:
1. Show that concatenating with `+` creates a new string object each time (immutable)
2. Use StringBuilder/list-join to efficiently build a string (mutable / efficient)
3. Compare the two approaches

## Examples

**Immutable approach (String concatenation):**
```
Input words: ["Hello", " ", "World", "!"]
Output: "Hello World!"
(Each + creates a new String object in memory)
```

**Mutable approach (StringBuilder / list join):**
```
Input words: ["Hello", " ", "World", "!"]
Output: "Hello World!"
(All appended to the same object — more efficient)
```

## Comparison

| Approach | Objects Created | Memory Efficient |
|----------|----------------|-----------------|
| `String +` operator | Multiple new objects | No |
| `StringBuilder` / join | Single object | Yes |
