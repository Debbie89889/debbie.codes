---
layout: post
title: "[LeetCode #1] Two Sum 解法"
---

這題使用 dictionary（字典）解法，時間複雜度 O(n) ✅

```python
def twoSum(nums, target):
    hashmap = {}
    for i, num in enumerate(nums):
        if target - num in hashmap:
            return [hashmap[target - num], i]
        hashmap[num] = i
