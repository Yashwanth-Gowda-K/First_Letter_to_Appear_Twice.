# First_Letter_to_Appear_Twice.


Problem Description
Given a string s, return the first character that appears twice (i.e., the first character where the second occurrence appears at a smaller index than any other duplicate character).

Key Points
The input string contains only lowercase English letters
The solution must efficiently identify the first duplicate character
Guaranteed at least one duplicate exists in the input

Solution Approaches
1. Hash Set Tracking (Optimal)
Time Complexity: O(n) - Single pass through the string
Space Complexity: O(1) - Uses fixed space (26 letters max)
Uses a hash set to track seen characters
Returns immediately upon finding the first duplicate

2. Frequency Array (Alternative)
Time Complexity: O(n) - Single pass through the string
Space Complexity: O(1) - Fixed-size array (26 elements)
Uses array indices to represent character counts
Similar performance to hash set approach

Performance Comparison
Approach	Time Complexity	Space Complexity	Best For
Hash Set	O(n)	O(1)	Most cases
Frequency Array	O(n)	O(1)	Memory-constrained
