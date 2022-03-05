# Program Structures & Algorithms

# Spring 2022

# Assignment No. 3

## Name:	Jashwanth Reddy Kamsani

## (NUID): 002988299

## Files present:
 1. Assignment pdf in submission format
 2. UF_HWQUPC (the file in which changes are made)

## Task:
1) (a) Implement height-weighted Quick Union with Path Compression.
(b) Check that the unit tests for this class all work.
2) Create a main program that takes n from the command line, calls count() and prints the returned value.
3) Determine the relationship between the number of objects (n) and the number of pairs (m)

## Conclusion:

As the number of objects(n) are increasing the number of pairs(m) changes linearithmic with n. 
To be more precise m is increasing n times the log of n to the base 5 which can be approximated to below expression.

m = n* log(n)

For larger values of n which is around 5000 to 20000, m value is nearly 5 times of n which can be seen in the evidence graph.

m = 5n

## Evidence / Graph: 
n      m      m/n
10    15      1.50
20    36      1.80
40    87      2.18
80    193     2.41
160   442     2.76
320   1031    3.22
640   2252    3.52
1280  4964    3.88
2560  10813   4.22
5120  23346   4.56
10240 49497   4.83
20480 107359  5.24



