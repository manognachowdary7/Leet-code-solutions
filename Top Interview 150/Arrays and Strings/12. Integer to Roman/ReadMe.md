## Approach: Greedy
### Idea
- Store Roman numeral values in descending order along with their symbols.
- Always choose the largest value that is less than or equal to the current number.
- Append the corresponding Roman symbol and subtract the value until the number becomes 0.

**Time Complexity:** O(1)

**Space Complexity:** O(1)
