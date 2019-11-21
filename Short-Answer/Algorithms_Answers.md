#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n)
The formula is linear. The bigger the input, the longer it takes to complete


b) O(n^3)
For Loops generally indicate O(n^2), in this case there are two of them.


c) O(n)
The formula is linear. The bigger the input, the longer it takes to complete

## Exercise II

Use binary search.

Lets say there are 8 floors.
Drop the egg at the middle floor, 4. If it breaks, keep dropping it at the next middle floor. In this case, floor 2. If that breaks continue at floor 1.
If it doesn't break at the middle floor, do the same thing but upwards. In this case, floor 6. If it breaks at floor 6, go to the middle floor which is 5. If it doesn't break, keep going.

We are repeatedly dividing the search interval in half.