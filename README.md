# simple-binary-search-js


## An example of binary search in javascript

Binary Search is searching technique which works on Divide and Conquer approach. It used to search any element in a sorted array.

As compared to linear, binary search is much faster with *Time Complexity of O(logN)* versus the linear search algorithm works in O(N) time complexity.

The Binary Search here is implemented in Javascript using both iterative and recursive ways are discussed.

Given a sorted array of numbers. The task is to search a given element x in the array using Binary search.

Examples:

`Input : arr[] = {1, 3, 5, 7, 8, 9}`

        x = 5

Output : Element found!


`Input : arr[] = {1, 3, 5, 7, 8, 9}`

        x = 6

Output : Element not found!

Note: Assuming the array is sorted.

The Algorithm:

BASE CONDITION: If starting index is greater than ending index return false.

Determine the middle index.
Compare the middle element with number x. If equal return true.
If greater, call the same function with ending index = middle-1 and repeat step 1.
If smaller, call the same function with starting index = middle+1 and repeat step 1.