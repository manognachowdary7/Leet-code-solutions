## Approach: Horizontal Scanning
### Idea:
- Take the first string as the initial prefix.
- Compare the prefix with each remaining string using startswith().
- If the current string doesn't start with the prefix, keep removing the last character until it matches or becomes empty.

**Time Complexity:** O(n × m)

- n = Number of strings
- m = Length of the shortest string

**Space Complexity:** O(1)