# BinarySearch

Look generally when we dont know solution we try to solve any question in O(n^2) then to O(n) and then to O(log n)
Binary Search is a tool to do it in O(log n)

LIMITATION : We can use it only when array is SORTED.

//374. Guess Number Higher or Lower
This question is just similar to normal binary search just inplace of mid comparison we are comparing it with guess api()


// we can also use it find any element and its first occurrence as well as last occurrence in the array.
--> Basic idea is that why we need this we can find occurence by foing linear search as well,but it would take O(n) time and we can reduce is to 0(log n) and this can be done by binary search

we will find the number then we will reduce the outer or increase the lower limit of search.
