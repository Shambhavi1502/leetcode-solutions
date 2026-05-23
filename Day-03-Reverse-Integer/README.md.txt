# Day 3 - Reverse Integer

## 🧩 Problem
Given a signed 32-bit integer, reverse its digits.  
Return 0 if the reversed integer overflows.

## 💡 Approach
- Extract digits using modulus (% 10)
- Build reversed number step by step
- Before updating, check for overflow:
  - If rev > Integer.MAX_VALUE / 10
  - Or rev < Integer.MIN_VALUE / 10 → return 0

## ⚙️ Complexity
- Time Complexity: O(log n)
- Space Complexity: O(1)

## 🚀 Example
Input: x = 123 → Output: 321  
Input: x = -123 → Output: -321  
Input: x = 120 → Output: 21  

## 📌 Key Learning
- Handling integer overflow without using long
- Writing safe and robust logic for edge cases