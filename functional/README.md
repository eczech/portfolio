# Functional Code Samples

These projects contain executable implementations of solutions for several problems.

Problems and Solutions:

- *Write a function to find the integer that appears most frequently in an iterable collection of integers*
    *<br>Example: f( [1, 2, 2, 5, 5, 5, 2, 2] ) = 2 (4 appearances)* 

    [Python Solution](/functional/cs_problems/python/most_frequent_item/lib.py) ([Unit Tests](/functional/cs_problems/python/most_frequent_item/test.py)) with time complexity **O( n^( 1+c ) )** and space complextiy **O( n^( 1-c ) + n^c )** where *c* is some configurable parameter on the range [0, .5].  See the documentation in the code for more details on how this implementation can be tuned appropriately based on the expected size of the given integer collection (i.e. *c* can be set to ensure that the space necessary is less than the size of the physical memory available).
    
- *Write a function to find the integer in an iterable collection of integers with the most consecutive appearances.*
    *<br>Example: f( [1, 2, 2, 5, 5, 5, 2, 2] ) = 5 (3 consecutive appearances)* 

    [Python Solution](/functional/cs_problems/python/most_consecutive_item/lib.py) ([Unit Tests](/functional/cs_problems/python/most_consecutive_item/test.py)) with time complexity **O(n)** and space complexity **O(1)**

