Add your answers to the Algorithms exercises here.
Exercise I
a) The running time is O(n) because it will take the n times to run in order break out of the while loop for any given n greater than 0.

b) The time complexity is O(n^4) because of the nested for loops that will for n's greater than 7. Otherwise smaller values of n won't go through all 4 nested for loops.

c) The running time is for n values is O(n) since it runs n - 1 times recursively for any n greater than 0.

Exercise II

a) I would apply my own divide and conquer method to find f floor. I would start with a midpoint value (n // 2) of n floors and check if eggs break at that floor and check if they don't break a floor below. If it's false, I would divide that section in half and recursively break it in half until I have a floor that breaks eggs and the floor below it that doesn't. Then I would return that floor number. If eggs do break at the original midpoint and don't break on the floor below, then I return that floor number.

The runtime complexity for this function would be O(log n) since the floors are sorted, I can be sure that I only need to look at half of the floors recursively to find floor f. I just keep dividing it until it satisfies my base case.


