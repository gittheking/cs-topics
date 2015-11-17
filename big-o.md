# Big O!

## Learning Objectives
1. What is Big O notation?
1. How do I find the `Big O` of an algorithm?
<!-- 1. Why is this important? -->


### What is Big O?
Big O is used to describe the behavior of the algorithm as input size grows. Another way of saying that is, it's used for approximating how long an algorithm takes to run.

With Big O we are able to express the runtime in terms of how quickly it grows relative to the input.

We will mostly be looking for the `WORST CASE SCENARIO` for each algorithm.

We are not looking for an exact number, but an order of magnitude. As N gets larger we drop the insignificant figures in the measurement
ex: `2n^2 + n + 1000`
The most significant magnitude here is `2n^2` which would give us and `T(n) = O(n^2)`).
**We do this because as N gets arbitrarily large, the less significant terms become, well, less significant.**

Give me the Big-O for:
1. 5x^3
1. 5x^2 + 2x^2 + 10
1. 1000n
1. 2n + 2
1. 10x^3 + 2x^2 + x + 125
1. 1
1. 10,000

### Pitfall of Big-O
1. Big-O ignores constants, but sometimes constants matter. If we have a script that takes 3 hours to run, an optimization that divides the runtime by 3 may not affect the Big-O, but it will still save you 2 hours of waiting.

1. optimizing algorithms can take up a lot of time and make your code unreadable. Sometimes it's more important to just write code that ships quickly.

### How do I find the timing complexity of an algorithm?
Show how expensive loops are with and without nesting.

show examples of linear, polynomial, and logarithmic functions

Constant time example:
finding a key from an associative array in JS
-Anytime you look something up from a hash it's cost is only O(1).



linear examples:
Searching for an element in an array/list using a for-loop.

^Finding the smallest or the largest in an array

Exponential example:

ANYTHING with nested for loops

```
for (i = 0; i < n; i ++){
  for (j = 0; j < n; j++ ){
    cosole.log("Hello!")
  }
}
```
