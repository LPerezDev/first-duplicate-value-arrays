# first-duplicate-value-arrays

ALGO EXPERT MEDIUM

Given an array of integers between *1* and *n*, inclusive, where *n* is the
length of the array, write a function that returns the first integer that
appears more than once (When the array is read from left to right).

In other words, out of all the integers that might occur more than once in the
input array, your function should return the one whose first duplicate value has
the minimum index.

If no integer appears more than once, your function should return *-1*.

Note that you're allowed to mutate the input array.

Sample input #1: <br>
array = [2, 1, 5, 2, 3, 3, 4] <br>

Sample output #1: <br>
2 <br>
(2 is the first integer that appears more than once. 3 also appears more than
once, but the second 3 appears after the second 2 does.)

Sample input #2: <br>
array = [2, 1, 5, 3, 3, 2, 4] <br>

Sample output #2: <br>
3 <br>
(3 is the first integer that appears more than once. 2 also appears more than
once, but the second 2 appears after the second 3 does.)
