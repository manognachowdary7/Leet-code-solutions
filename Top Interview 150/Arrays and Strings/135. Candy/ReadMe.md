## Approach: Two-Pass Greedy
### Idea:
- Give every child 1 candy initially since each child must receive at least one candy.
- Traverse left to right. If a child has a higher rating than the left neighbor, give one more candy than the left neighbor.
- Traverse right to left. If a child has a higher rating than the right neighbor, update the candies using max() to satisfy both left and right neighbor conditions.

**Time Complexity:** O(n)

**Space Complexity:** O(n)