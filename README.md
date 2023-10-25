# linear-binary-search-algorithms
Search algorithms are a fundamental computer science concept that you should understand as a developer. They work by using a step-by-step method to locate specific data among a collection of data.

Search algorithms are designed to check or retrieve an element from any data structure where that element is being stored. They search for a target (key) in the search space.

Types of Search Algorithms In this post, we are going to discuss two important types of search algorithms:

1.Linear or Sequential Search 2.Binary Search

LINEAR SEARCH

Assume that item is in an array in random order and we have to find an item. Then the only way to search for a target item is, to begin with, the first position and compare it to the target. If the item is at the same, we will return the position of the current item. Otherwise, we will move to the next position. If we arrive at the last position of an array and still can not find the target, we return -1. This is called the Linear search or Sequential search.

![image](https://github.com/Preet-Sawant-9/linear-binary-search-algorithms/assets/130697042/ea6d5abf-1209-4903-bad2-7f68c4235ebe)


BINARY SEARCH

Binary Search is a search algorithm that is faster than the linear search algorithm. Binary Search is used to search the position of the target element in a sorted array by repeatedly dividing the search space in half. Binary search eliminates half portion of the array with each comparison. It works in a time complexity of O(log n) where n is the number of elements in the array.

![image](https://github.com/Preet-Sawant-9/linear-binary-search-algorithms/assets/130697042/b8568b3d-07b5-496e-bcd3-d6684c12418d)


ALGORITHM
Algorithm for User Input - Linear Search and Binary Search:

Start.

Initialize an empty array or list (arr) to store the data.

Prompt the user to input the size of the array (n).

Create a loop to input 'n' elements from the user into the array (arr).

Prompt the user to input the target element (target) they want to search for.

Perform Linear Search:

a. Set a variable 'found' to false.

b. For each element in the array (arr):

 i. If the current element is equal to the target:

     - Set 'found' to true.

     - Print "Element found at index [index]".

     - Break the loop.
c. If 'found' is still false, print "Element not found in the array".

Perform Binary Search (assuming the array is sorted):

a. Initialize 'low' to 0 (the first index) and 'high' to n - 1 (the last index).

b. While 'low' is less than or equal to 'high', repeat the following:

 i. Calculate the middle index 'mid' as (low + high) / 2.

 ii. If the element at 'mid' is equal to the target:

     - Print "Element found at index [mid]".

     - Exit the loop.

 iii. If the element at 'mid' is less than the target, set 'low' to 'mid' + 1.

 iv. If the element at 'mid' is greater than the target, set 'high' to 'mid' - 1.
c. If the loop exits without finding the target, print "Element not found in the array."

End.

OUTPUT
![image](https://github.com/Preet-Sawant-9/linear-binary-search-algorithms/assets/130697042/863cb92b-3183-4a00-9ae0-71bfea9b220a)
