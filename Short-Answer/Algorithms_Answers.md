#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) O(log n)
This is because the value of a increases exponentially but the runtime increases marginally. The rate of increase of the runtime is slower than the rate of increase of the value of a.

b) O(n log n)
The runtime for increases slightly faster than the rate of increase in n. The "for loop" code part has a O(n), and the "while loop" has O(log n). Combination of which givesus the linearithmetric runtime of O(n log n).

sum = 0
for i in range(n): # O(n)
j = 1
while j < n:
j \*= 2 # O(log n)
sum += 1

c) O(2^n) - Exponential

The runtime increases at a much faster rate than the increase in n.

## Exercise II
