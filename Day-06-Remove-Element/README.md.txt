# Day 6 - Remove Element (LeetCode 27)

## 🧩 Problem
Given an integer array `nums` and an integer `val`, remove all occurrences of `val` in-place.  
Return the number of elements not equal to `val`.

## 💡 Approach
- Used **two-pointer technique**
- One pointer (`i`) traverses the array
- Another pointer (`k`) stores position for valid elements
- If element ≠ `val`, place it at index `k` and increment `k`

## ⚙️ Complexity
- Time Complexity: O(n)
- Space Complexity: O(1)

## 🚀 Example
Input: nums = [3,2,2,3], val = 3  
Output: 2, nums = [2,2,_ , _]

Input: nums = [0,1,2,2,3,0,4,2], val = 2  
Output: 5, nums = [0,1,4,0,3,_ , _ , _]

## 📌 Key Learning
- In-place array modification  
- Two-pointer pattern  
- Efficient filtering without extra space