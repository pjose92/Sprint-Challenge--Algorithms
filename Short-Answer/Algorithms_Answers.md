#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) - one simple loop

b) O(n ^ 2) - nested loop

c) O(n) - recursive function that runs n times until it dwindles down to zero.

## Exercise II

it would be a binary search

def broken_egg(egg, floor):
    ground = 0
    top = floor - 1

    while ground <= top:
        current = (ground + top) // 2
        if egg.drop_from(current) == "Not Broken":
            ground = current
        else:
            return current
This would be O(log n) since n (floor) gets divided each loop.
