#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)  O(n^3)
- This will run at most n^3 times dur to the n\*n*n in line 10

b)  O(n^log(n))
-  The outer loop runs n times x the inner loop which is log(n) due to the growth rate of j


c)  O(n)
- This recurses n times

## Exercise II


I would do it like a binary search, start at 1/2 n, keep halving until one doesn't break, then climb back up and take the second to last one after one breaks
Probably a memoized tail recursive function that passes the laregets non-breaking n back as f