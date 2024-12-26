[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XE8_Ygzq)
[![Work in MakeCode](https://classroom.github.com/assets/work-in-make-code-8824cc13a1a3f34ffcd245c82f0ae96fdae6b7d554b6539aec3a03a70825519c.svg)](https://classroom.github.com/online_ide?assignment_repo_id=17598610&assignment_repo_type=AssignmentRepo)
# DAY-5

## Table of Contents

1. [Searching a Number](#1-searching-a-number)
2. [Squares of a Sorted Array](#2-squares-of-a-sorted-array)
3. [Search in a 2D Matrix](#3-search-in-a-2d-matrix)
4. [Merge k Sorted Lists](#4-merge-k-sorted-lists)
5. [Median of Two Sorted Arrays](#5-median-of-two-sorted-arrays)

---

## 1. Searching a Number

### Problem Statement:
Given an integer `k` and an array `arr`, find the position of the first occurrence of `k` in the array. Return `-1` if `k` is not present. **1-based indexing** is followed.

### Example:
- **Input:** `k = 16`, `arr = [9, 7, 16, 16, 4]`
- **Output:** `3`

- **Input:** `k = 98`, `arr = [1, 22, 57, 47, 34, 18, 66]`
- **Output:** `-1`

### Constraints:
- Array length: 1 ≤ `arr.length` ≤ 10⁵
- Element values: -10⁵ ≤ `arr[i]` ≤ 10⁵

---

## 2. Squares of a Sorted Array

### Problem Statement:
Given a sorted array, return an array of the squares of each number in sorted non-decreasing order.

### Example:
- **Input:** `nums = [-4, -1, 0, 3, 10]`
- **Output:** `[0, 1, 9, 16, 100]`

- **Input:** `nums = [-7, -3, 2, 3, 11]`
- **Output:** `[4, 9, 9, 49, 121]`

### Constraints:
- 1 ≤ `nums.length` ≤ 10⁴
- -10⁴ ≤ `nums[i]` ≤ 10⁴
- `nums` is sorted in non-decreasing order.

---

## 3. Search in a 2D Matrix

### Problem Statement:
Given a 2D matrix where:
1. Each row is sorted in non-decreasing order.
2. The first integer of each row is greater than the last integer of the previous row.

Write a function to search for a target in the matrix. Return `true` if found, otherwise `false`.

### Example:
- **Input:** `matrix = [[1,3,5,7],[10,11,16,20],[23,30,34,60]], target = 3`
- **Output:** `true`

- **Input:** `matrix = [[1,3,5,7],[10,11,16,20],[23,30,34,60]], target = 13`
- **Output:** `false`

### Constraints:
- 1 ≤ `m, n` ≤ 100
- -10⁴ ≤ `matrix[i][j], target` ≤ 10⁴

---

## 4. Merge k Sorted Lists

### Problem Statement:
Given an array of `k` linked-lists, each sorted in ascending order, merge them into one sorted linked-list.

### Example:
- **Input:** `lists = [[1,4,5],[1,3,4],[2,6]]`
- **Output:** `[1,1,2,3,4,4,5,6]`

- **Input:** `lists = []`
- **Output:** `[]`

### Constraints:
- `0 ≤ k ≤ 10⁴`
- `0 ≤ lists[i].length ≤ 500`
- -10⁴ ≤ `lists[i][j]` ≤ 10⁴
- The sum of all `lists[i].length` will not exceed 10⁴.

---

## 5. Median of Two Sorted Arrays

### Problem Statement:
Given two sorted arrays `nums1` and `nums2`, return the median of the two sorted arrays in O(log(m + n)) time complexity.

### Example:
- **Input:** `nums1 = [1,3]`, `nums2 = [2]`
- **Output:** `2.00000`

- **Input:** `nums1 = [1,2]`, `nums2 = [3,4]`
- **Output:** `2.50000`

### Constraints:
- 0 ≤ `nums1.length, nums2.length` ≤ 1000
- 1 ≤ `nums1.length + nums2.length` ≤ 2000
- -10⁶ ≤ `nums1[i], nums2[i]` ≤ 10⁶

