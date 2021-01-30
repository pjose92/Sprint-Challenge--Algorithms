#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n). While loop will not stop until a > n^3. The increment every time is n^2. n^3 / n^2 = n. It takes nth to run the loop regardless of n value. 


b)O(n log n): for loop will run nth times, the nested wile loop run n/2 times. Exiting the while loop the j value will be over written. 


c)O(n): this function will call "bunnies" time before reach base case

## Exercise II

Using binary search so that we don't go through every floor. Binaray search will also minimize drooped eggs and broken eggs.

Will be starting by the midpoint, separating floors into a lower and higher list. Checking if egg breaks at midpoint floor. If egg breaks at midpoint floor then we will eliminat the upper level floors and repeat. We will repeat floor separation and midpoint check on the lower floor list. If egg didn't break then repeat floor separation and midpoint check on the hugher floors. Will continue midpoints checks until list is invisible then return floor.

Algorithim has a logarithmic time complexity O(log n) because it doesnt run through all the values but also relies on number of floors


