# Search Insert Position

**Date:** 2026-11-25  
**Difficulty:** 🟢 **Easy**  
**Tags:** `Array` `Binary Search`

## Problem Description

Given a sorted array of distinct integers and a target value, return the index if the target is found. If not, return the index where it would be if it were inserted in order. You must write an algorithm with O(log n) runtime complexity. Example 1: Input: nums = [1,3,5,6], target = 5 Output: 2 Example 2: Input: nums = [1,3,5,6], target = 2 Output: 1 Example 3: Input: nums = [1,3,5,6], target = 7 Output: 4 Constraints: 1 <= nums.length <= 10 4 -10 4 <= nums[i] <= 10 4 nums contains distinct values sorted in ascending order. -10 4 <= target <= 10 4

[LeetCode Link](https://leetcode.com/problems/search-insert-position)

## Approach

Unknown

> Analysis unavailable

## Solution Logic

1. Could not analyze solution

## Complexity Analysis

| Complexity | Analysis |
|------------|----------|
| **Time:** | Unknown |
| **Space:** | Unknown |

## Edge Cases Handled

None specified

## What I Learned

AI analysis failed — solution still committed to GitHub

## Similar Problems

None suggested

## Solution Code

```text
class Solution {
    public int searchInsert(int[] nums, int target) {
        for(int i=0;i<nums.length;i++){
            if(nums[i]>=target){
                return i;
            }
        }
        return nums.length;
    }
}
```
