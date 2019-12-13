#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)
This snippet of pseudocode seems to have a linear runtime because it seems the time to run will grow at the same rate as input size increases.

b)
Polynomial runtime O(n^c) . As the size of the input increases, the runtime will grow at a faster rate.

c)
Linearithmic runtime O(n log n). As the size of the input increases, the runtime will grow at a tlightly faster rate.

## Exercise II

Implement binary search


List floors in an array (assume already ordered) Split the number of floors in the middle
set min to array 0 set max to array length 
find midpoint (//2)
check to see if egg breaks when dropped from largest floor before midpoint 
if yes go no higher (aka eliminate higher floors)
if no go to midpoint and drop egg
if egg breaks, go no higher (eliminate floors higher than this new midpoint) 
if no, go to midpoint, and drop egg
repeat until the highest floor the egg will not break on is found


