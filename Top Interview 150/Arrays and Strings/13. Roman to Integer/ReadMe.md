## Approach: Hash Map + String Traversal
### Idea:
- Store Roman numerals and their corresponding values in a hash map.
- Traverse the string from left to right and compare the current symbol with the next symbol.
- If the current value is smaller than the next value, subtract it; otherwise, add it to the total.
**Time Complexity:** O(n)

**Space Complexity:** O(1)