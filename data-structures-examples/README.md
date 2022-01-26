# Some basic data structures examples-solutions <img src="https://uploads-ssl.webflow.com/6097e0eca1e87557da031fef/609859a191abe5d64b17fed3_Patika%20logo-p-500.png" width="70px">  

## Project 1

__[22,27,16,2,18,6] -> Insertion Sort__

* ### Write the stages of the above sequence according to the sort type.
```
[22,27,16,2,18,6] --> (n)
[2,27,16,22,18,6] --> (n-1)
[2,6,16,22,18,27] --> (n-2)
[2,6,16,18,22,27] --> (1)
```
* ### Write the Big-O notation.
```
= n + (n-1) + (n-2) + 1

= n.(n+1) / 2 

= (n² + n) / 2 

= O(n²)
```
* ### Time Complexity: Average case: The number we are looking for is in the middle, Worst case: The number we are looking for is at the end, Best case: The number we are looking for is at the beginning of the series.
```
Average Case : [2,6,16,18,22,27] = 16 - 18 / O(n²)
Worst case   : [2,6,16,18,22,27] = 27 / O(n²)
Best case    : [2,6,16,18,22,27] = 2 / O(n²)
```
* ### What case does the number 18 fall into after the array is sorted? Write.
```
[2,6,16,-18-,22,27] = Average case
```
-----
## Project 2
__[16,21,11,8,12,22] -> Merge Sort__
* ### Write the stages of the above array according to the sort type.
```
                    [16,21,11,8,12,22]
                  [16,21,11]   [8,12,22]
              [16] - [21,11]   [8] - [12,22]
          [16] - [21] - [11]   [8] - [12] - [22]
              [16] - [11,21]   [8] - [12,22]
                  [11,16,21]   [8,12,22]
                    [8,11,12,16,21,21]
```
* ### Write the Big-O notation.
```
O(nlogn)
```
----
## Project 3
__[7,5,1,8,3,6,0,9,4,2]->Binary-Search-Tree__
* ### Root=7
```
           7
         /   \
        5     8
       / \     \
      1   6     9
     / \
    0   3
       / \
      2   4

```


