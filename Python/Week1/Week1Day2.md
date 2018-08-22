# Week1
## Day 2
**Objective: Know the basic operations**
**Useful Link: **
**1. https://www.learnpython.org/en/Basic_Operators**
** **

Run the following code in Python: 
```
print("The / operator does 'normal' float division:")
print(" 5/3  =", ( 5/3)) # We get a long decimal number
print()
print("The // operator does integer division:")
print(" 5//3 =", ( 5//3)) #What is the type of the result?
print(" 2//3 =", ( 2//3))
print("-1//3 =", (-1//3))
print("-4//3 =", (-4//3))
```
Expected result:
```
The / operator does 'normal' float division:
5/3  = 1.6666666666666667

The // operator does integer division:
5//3 = 1
2//3 = 0
-1//3 = -1
-4//3 = -2
```
What's the differene between / and //
Does "//" round up or round down?

Run the following code in Python: 
````
print(" 6%3 =", ( 6%3))
print(" 5%3 =", ( 5%3))
print(" 2%3 =", ( 2%3))
print(" 0%3 =", ( 0%3))
print("-4%3 =", (-4%3))
print(" 3%0 =", ( 3%0))# It doesn't work! Can you divide a number by 0?
````
Expected result:
```
6%3 = 0
5%3 = 2
2%3 = 2
0%3 = 0
-4%3 = 2
Traceback (most recent call last):
(............)
ZeroDivisionError: integer division or modulo by zero
```
The "%" operator takes the reminder of a division

Problem to try:
1. getKthDigit(n, k) 
Write the function getKthDigit(n, k) that takes a possibly-negative int n and a non-negative int k, and returns the kth digit of n, starting from 0, counting from the right. So:
getKthDigit(789, 0) returns 9
getKthDigit(789, 2) returns 7
getKthDigit(789, 3) returns 0
getKthDigit(-789, 0) returns 9 

2. isPerfectSquare(n) 
Write the function isPerfectSquare(n) that takes a possibly-non-int value, and returns True if it is an int that is a perfect square (that is, if there exists an integer m such that m**2 == n), and False otherwise. Do not crash on non-ints nor on negative ints.



