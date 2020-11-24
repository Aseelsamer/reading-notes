## Concepts of Functional Programming in Javascript

-What is functional programming?
Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data .

-How to know if function is pure It returns the same result if given the same arguments (it is also referred as deterministic)
It does not cause any observable side effects.

NOTE:***Any function that relies on a random number generator cannot be pure.***

-We have the counter value. Our impure function receives that value and re-assigns the counter with the value increased by 1.

pure functions + immutable data = referential transparency

-When we talk about higher-order functions, we mean a function that either:
takes one or more functions as arguments, or
returns a function as its result
-The doubleOperator function we implemented above is a higher-order function because it takes an operator function as an argument and uses it

-The map method transforms a collection by applying a function to all of its elements and building a new collection from the returned values.

-We use the Math.abs function to transform the value into its absolute value, and do the in-place update

-The idea of reduce is to receive a function and a collection, and return a value created by combining the items.


