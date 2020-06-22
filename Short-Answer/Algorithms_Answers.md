#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) O(n)


b) O(n log n)
The runtime for increases slightly faster than the rate of increase in n. The "for loop" code part has a O(n), and the "while loop" has O(log n). Combination of which givesus the linearithmetric runtime of O(n log n).

sum = 0
for i in range(n): # O(n)
j = 1
while j < n:
j \*= 2 # O(log n)
sum += 1

c) O(n) 


## Exercise II
The first pass approach will be to keep increasing the floor count until we find out the first where eggs get broken. This will lead to waste of eggs as many eggs will have to be smashed. 

On the other hand, we can use the concept of a binary tree. This means we can have a target floor. The values to the right of the tree will be denoted by the floor that are above our target floor. The values to the left will be the values below our target floor. This way, we can minimize the number of eggs that will be smashed.
