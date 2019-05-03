Add your answers to the Algorithms exercises here.

1) a) O(n^3), cubic. The while loop multiples n by itself 3 times, and continues until it reaches that number.

b) O(n^4), quartic or polynomial. There are 4 nested loops, n is multipled by itself for each loop.

c) O(n), linear. This is slightly tricky because of the recursive call so you might think it is O(n^2), but actually since bunnies is n, you are calling this function recusively n times before you reach the base case, its a single loop in a recursive call, so linear time.



2) Of the methods I am familiar with, I think a binary search minimizes the number of checks you need to make with the data. I would go to the middle floor and see if the egg breaks when I drop the egg, if it does I would eliminate the top half of the building, if not, I would eliminate the bottom half. I would then cut that half of the building in half again, and check the 1/4 or 3/4 value of _f_. I would repeat this process until I got the value of _f_.

