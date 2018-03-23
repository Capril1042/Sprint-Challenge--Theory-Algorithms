 # Answers for Analysis of Algorithms

 ## Exercise I-Answers
 a) O(n)- Linear Time - number of steps is directly related to n, because even though we are steping through this while a < n*n*n times- each time we make  a step we change a  to a + n*n.
 b) O(log(n))- Logarithmic Time- the number of steps decreases with each step taken, because each step we divide i by 2.
 c) O(sqrt(n))- Square Root Time - the number of steps  is related to square root of n, because we step thorugh it Math.sqrt(n)/2 times and then
 d) O(nlogn)- Quasilinear Time - Outer loop is O(log(n)) and inner loop is O(n).
 e) O(n^3)- Cubic Time - Three linear O(n) loops one constant O(1) loop.
 f) O(n)- Linear Time - number of steps is directly related to n 
 g) O(n)- Linear Time - number of steps is directly related to n

 ## Exercise II- Answers
 a)
 b) My strategy to determine the value of `f` would be to drop my first egg from floor `n/2` - the middle floor i'd call this floor `m'. If the egg did not break I would then drop the egg from floor `(n/4)+m`- the middle of the top half of floors. If the egg still didn't break I would contine in this pattern- finding the halfway point betwene the last floor the egg was dropped and n. Once the egg did break I would calculate the halfway-point betwen the last non-breaking point and the newly found upper breaking point point `bp'. I would then drop the egg at the new halfway point and continue in the same fashion.
 If the egg had broken on my first drop I would take the smae stratgey except I would be taking the halfway point betwen the bott0m floor and the floor the the egg first broke on.

 ## Exercise III- Answers 
 a) If the array is already sorted, and the pivot chosen is the first element of the array; the running time of this algorithm would be (On^2).
 b) If the pivot was magically the median element then the running time of the algorthm would be O(n).