# CCC
Q.1
Binary Flips
A Onely sequence is a sequence consisting of 1 only.

For example : {1,1,1,1} is a onely sequence while {1,2,1} is not.

You are given with an array of 1s and 0s. And you are given with an integer M, which signifies number of flips allowed.

Each flip can be used as follows :
- If an element is 1, it can be changed to 0.
- If an element in 0, it can be changed to 1.

You are to apply at most M flip operations to product the longest continuous sequence of 1s in the array.

For this problem, return the indices of maximum continuous series of 1s in order.

Input Format

First line contains N and M, the size of array and number of flips allowed. Second line contains N integers, the elements of array a.

Constraints

1 <= N,M <= 10^5

Output Format

Output two numbers, the starting and the ending index (1-indexed) of the longest Onely sequence.

In case of multiple answers print the one with lower start index.

Sample Input 0

10 1
1 1 0 1 1 0 0 1 1 1

Sample Output 0

1 5

