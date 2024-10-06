## Question 1

Binary search is a searching algorithm that finds an element n in a sorted list L of size s. Firstly it compares n to L[s//2]. If n is bigger than L[s//2], it means that n is in upper half of the list. Likewise, if n is smaller than L[s//2], it means n is in lower half of the list. Then, the half of list which does not contain n is discarded. This process repeated until k th step where L[s//2**k] equals to n or list is empty.

Write a function which implements binary search to find whether or nor a float exists in a list of floats.

| Input                                     | Output                    |
| ----------------------------------------- | ------------------------- |
| L = [ 1 , 3 , 4 , 5 , 6] , num = 5        | 5 exists in list          |
| L = [ 21 , 13 , 4.4 , 85 , 60] , num = 16 | 16 does not exist in list |

## Question 2

A number is said to be "Disarium" if the sum of its digits raised to their respective positions is the number itself. Write a program that determines whether a number is a Disarium or not.

75 ➞ False

*7^1 + 5^2 = 7 + 25 = 32*

135 ➞ True

*1^1 + 3^2 + 5^3 = 1 + 9 + 125 = 135*

Example Inputs/Outputs:

544 ➞ False

518 ➞ True

466 ➞ False

8 ➞ True


## Question 3

In number theory, [Euler's Totient function](https://en.wikipedia.org/wiki/Euler's_totient_function) counts the positive integers up to a given integer *n* that are relatively prime to n. Write three functions, respectively `gcd(a, b)`, `relatively_prime(a, b)` and `euler_totient(a)`. To find `euler_totient(a)`, count the number of integers between 1 and *n* that are relatively prime with *n*. A number *a* is relatively prime with *b* iff `gcd(a, b) = 1`. To implement `gcd(a, b)`, follow the steps below. Given an integer *n*, print out the `euler_totient(n)`. To find the greates common divisor between *a* and *b*:

- Repeatedly replace (*a*,*b*) with (*b*,*a %* b) until the second integer in the pair is zero.
- Return the first integer in the pair as the gcd.

| INPUT | OUTPUT |
| ----- | ------ |
| 10    | 4      |
| 342   | 108    |
| 76    | 36     |
