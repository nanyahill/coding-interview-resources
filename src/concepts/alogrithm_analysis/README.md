Algorithms are easily understood and studied in a language- and machine-independent.
The running time of an algorithm is the number of computational steps used by the algorithm to solve a given problem instance of size n.
Growth rate of an algorithm: The rate at which the time and space requirements grow as the input size grows.

Asymptotic notation describes the upper, lower, and tight bounds of the run-times (or growth rate) of an algorithm. There are generally three notations:
Big O (describes the upper bound of growth rate): f(n) = O(g(n)) iff there exists a constant c such that f(n) <= c.g(n) for large values of n.
Big Omega (describes the low bound of growth rate): f(n) = Big Omega(g(n)) iff there exists a constant c such that f(n) >= c.g(n) for large values of n.
Big Theta (describes the tight bound of growth rate): f(n) = Big Theta(g(n)) iff there exists a constants c1 and c2 such that f(n) <= c1.g(n) and f(n) >= c2.g(n) for large values of n.


Asymptotic notations can be further described based on particular inputs/scenarios using three different ways:
Worst-case: The maximum number of steps taken in any given instance of the problem.
Example: In Quicksort, an input of n elements where the pivot is always the largest element would split the input into two unequal halves- one of size 1 and the other of size n-1.

Best-case: The minimum number of steps taken in any give instance of the problem.
Example: In Quicksort, an input of n elements where the pivot is always the middle element would split the input into two equal halves- one of size n/2 and the other of size n/2.

Average-case: The average number of steps over all instances of n.
Example: In Quicksort, an input of n elements where the pivot not always the largest element.

In practice, the Big O and the worst case analysis are more useful in describing the efficiency of an algorithm.

Notes:
- Any memory allocated besides the input count towards the space complexity.
- Variables have a constant space complexity because the numbe of variables stay the same regardless of the size of n.

*** Made more sense to me that ever before ****
Usually in AlgorithmAnalysis we are looking for upper bounds on cost, as in "Algorithm X solves problem Y in no more than O(n22/7) time in the worst case."
Upper bounds are useful when we want to advertise that our algorithm is good. But what if we want to argue that no other algorithm can be better, or perhaps
that some problem is so hard that we can't possibly hope to find a good solution to it?
Source: http://www.cs.yale.edu/homes/aspnes/pinewiki/LowerBounds.html

Upper bound is the big theta bound on the worst case running time.
It is used to advertise that the algorithm is good- the algorithm can not get an input that would make this running time worse.

Lower bound is the big omega bound on the worst case running time.
It is used to advertise that the algorithm is bad- no other algorithm can be better, or perhaps that some problem is so hard that we can't possibly hope to find a good solution to it?

Big O on the worst case running time is when big omega = big theta (both on the worst case running time).

Good link on recurrence relations of common algorithms, e.g binary search: http://faculty.simpson.edu/lydia.sinapova/www/cmsc250/LN250_Weiss/L14-RecRel.htm
