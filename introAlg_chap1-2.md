Chapter 1
=========
## The Role of Algorithms in Computing

Definition- Any well- defined computational procedure that takes some value, or set of values as input and produces some value or set of values as output.
__Example__: Sorting 
* Input -A sequence of n numbers { a, a2, ….aN}
* Output - A permutation such that a1 < a2 < . . . < aN}
**Data Structures**
Def - way to store and organize data in order to facilitate access and modifications.
Algorithms as a Technology
Efficiency
resources are limited, and algorithms make up for that
Technology

Chapter 2
=========
## Getting Started
Insertion sort
numbers are know as keys, and they come from and array with n elements
loop invariants and Correctness of insertion sort
Initialization: it is true prior to the first iteration of the loop
Maintenance: If it is true before an iteration of the loop, it remains true before the next iteration
Termination: When the loop terminates the invariant gives us a usseful property that helps show that the algorithm is correct.
Analyzing Algorithms
Def- predictin the resources that the algorithm requires.
(RAM) random-access machine model of computation
instructions executed one after another
Doesn't model memory-hierarchy effects.
Input size
number of items in the input
or total number of bits needed to represent the input
Running Time
each line takes constant amount of time
Worst case and average case analysis
worst case is better because:
gives us upper bound on the running time for any input
worst case occurs fairly often
“average case” usually roughly as bad as the worst case.
If we are interested in average case, we can use a probabilistic analysis 
Then we would use randomized algorithms
Order of Growth
ignore the leading terms constant and lower order terms- unimportant
Designing Algorithms
Incremental approach - insertion sort
divide and conquer  
