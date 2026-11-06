Roman to Integer

Problem

Convert Roman numerals into integers.

Language

Java

Platform

LeetCode

Approach

1. Traverse the string using a for loop.
2. Find the value of each Roman character.
3. Compare the current character with the next character.
4. Subtract if the current value is smaller.
5. Otherwise, add the value.
6. Return the total.

Time Complexity

O(n)

Space Complexity

O(1)
