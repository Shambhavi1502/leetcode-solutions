# Day 5 - Remove Duplicates from Sorted Array (LeetCode 26)

## 🧩 Problem
Given a sorted array `nums`, remove duplicates in-place such that each unique element appears only once.  
Return the number of unique elements `k`.

## 💡 Approach
- Used **two-pointer technique**
- One pointer (`i`) tracks position of unique elements
- Second pointer (`j`) scans the array
- When a new element is found, update position and move pointer

## ⚙️ Complexity
- Time Complexity: O(n)
- Space Complexity: O(1)

## 🚀 Example
Input: nums = [1,1,2]  
Output: 2, nums = [1,2,_]  

Input: nums = [0,0,1,1,1,2,2,3,3,4]  
Output: 5, nums = [0,1,2,3,4,_...]

## 📌 Key Learning
- Two-pointer technique for array problems  
- In-place modification without extra space  
- Efficient duplicate handling in sorted arrays