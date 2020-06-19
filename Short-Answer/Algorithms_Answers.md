#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) This algorithm is `O(n)`. This sets a variable `a` to zero and runs through a single `while` loop where as long as `a` is less than `n*n*n`,  it will reassign itself to `a` plus `n*n`. it's `O(n)` complexity because it increases with each increase of input.


b) This algorithm is `O(n Log(n))`. This is because it is a loop within a loop. The outer loop is `O(n)` with a simple for-loop. the inner loop is `O(log(n))` because it increases twice as fast with each pass. combining them together creates `O(n log(n))`.


c) This algorithm utilizes recursion. using a base-case for then `bunnies == 0` it can safely loop over itself until it counts all of the bunny ears. Each runtime is just 1 input causing this algorithm to be `O(n)`.

## Exercise II

# Create a list of floors to count from
# Create an iterator to count through the floors
# Create the highest floor value
# Creat the lowest floor value

Because we're trying to find the best window with the least number of guesses, i would impliment a binary tree algorithm by testing the midpoint first. Depending on the result, i would cut the remaining floors in half again, and again, until finding the solution. The runtime complexity of this algorithm would be `O(Log n)`