---
title: Smallest element in an array that is repeated exactly ‘k’ times.
permalink: /smallest-element-array-repeated-exactly-k-times/
tags: [Arrays, Sorting, limited-range-elements]
---

Given an array of size n, the goal is to find out the smallest number that is repeated exactly ‘k’ times where k > 0?
Assume that array has only positive integers and 1 <= arr[i] < 1000 for each i = 0 to n -1.

Examples:

```
Input : arr[] = {2 2 1 3 1}
        k = 2
Output: 1
Explanation:
Here in array,
2 is repeated 2 times
1 is repeated 2 times 
3 is repeated 1 time
Hence 2 and 1 both are repeated 'k' times
i.e 2 and min(2, 1) is 1

Input : arr[] = {3 5 3 2}
        k = 1
Output : 2
Explanation:
Both 2 and 5 are repeating 1 time but
min(5, 2) is 2
```

source: http://www.geeksforgeeks.org/smallest-element-array-repeated-exactly-k-times/
