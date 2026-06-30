## Approach: Greedy
### Idea:
- Check if the total gas is less than the total cost. If yes, return -1 because completing the circuit is impossible.
- Traverse all gas stations while maintaining the current fuel (tank).
- If the tank becomes negative, the current starting station cannot complete the circuit. Set the next station as the new starting point and reset the tank to 0.

**Time Complexity:** O(n)

**Space Complexity:** O(1)