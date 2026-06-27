## Approach: Greedy
### Idea
- Traverse the array and compare each day's price with the previous day's price.
- If today's price is higher, add the profit (prices[i] - prices[i - 1]).
- Sum all positive profits to get the maximum total profit.

**Time Complexity:** O(n)

**Space Complexity:** O(1)
