# Day 4 - Roman to Integer

## 🧩 Problem
Convert a Roman numeral string into an integer.

## 💡 Approach
- Traverse the string from left to right
- Convert each Roman character to its integer value
- If current value < next value → subtract it
- Otherwise → add it

## ⚙️ Complexity
- Time Complexity: O(n)
- Space Complexity: O(1)

## 🚀 Example
Input: s = "III" → Output: 3  
Input: s = "IV" → Output: 4  
Input: s = "IX" → Output: 9  

## 📌 Key Learning
- Handling special subtraction cases in patterns
- Efficient string traversal and comparison