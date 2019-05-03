Add your answers to the Algorithms exercises here.

1) a) O(n), linear, the function is called once.

b) O(n^4), quartic or polynomial. There are 4 nested loops, n is multipled by itself for each loop.

c) O(n), linear. This is slightly tricky because of the recursive call so you might think it is O(n^2), but actually since bunnies is n, you are calling this function recusively n times before you reach the base case, its a single loop in a recursive call, so linear time.