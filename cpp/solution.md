# 2200. Find All K-Distant Indices in an Array

## Problem
Given an array `nums`, a `key`, and an integer `k`, return all indices `i` such that `|i - j| <= k` for some `j` where `nums[j] == key`.

## Solution
- Loop through array and find indices where `nums[i] == key`.
- For each, include `i-k` to `i+k` in the result set (within bounds).
- Return sorted list of unique indices.

## Language: C++
