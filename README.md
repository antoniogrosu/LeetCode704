
# Binary Search

Given an array of integers nums which is sorted in ascending order, and an integer target, write a function to search target in nums.
If target exists, then return its index. Otherwise, return -1.

You must write an algorithm with O(log n) runtime complexity.


## My Solution

The given C++ code performs a binary search algorithm to find a target value in an array of integers named 'v' of size up to 10001. The binarySearch function takes two arguments, an integer array v and an integer target.

The function first checks the number of elements in the array 'v' that are greater than their previous element or are the first element in the array, as well as the number of elements that are less than the following element or are the last element in the array. These counts are stored in 'r' variable.

Then the function initializes two pointers, 'left' and 'right', for the binary search. It repeatedly calculates the middle index 'mid' using the average of the 'left' and 'right' indices and checks if the target value is present at that index. If it is, the function returns the index.

If the target value is not found at the middle index, it adjusts either the left or the right pointer based on whether the middle value is less than or greater than the target value, respectively.

If the target value is not found in the array, the function returns -1.

Overall, the algorithm performs a binary search in O(log n) time complexity to find the target value in a sorted array.

## Tech Stack

**Language:** C++

## LeetCode Problem

 - [704 Binary Search](https://leetcode.com/problems/binary-search/?envType=study-plan&id=algorithm-i)

