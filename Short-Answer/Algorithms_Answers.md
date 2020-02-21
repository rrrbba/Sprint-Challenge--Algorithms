#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I
```python
a)  a = 0
    while (a < n * n * n):
      a = a + n * n
```
a) The run time complexity of the above problem is O(n). I say this because the run time will grow at the same rate as the input size increases.




```
b)  sum = 0
    for i in range(n):
      j = 1
      while j < n:
        j *= 2
        sum += 1
```
b) The run time complexity for this one is O(n^2). I know this because the for loop's run time complexity is O(n), however once you get to the while loop the loop is multiplied by 2.






```
c)  def bunnyEars(bunnies):
      if bunnies == 0:
        return 0

      return 2 + bunnyEars(bunnies-1)
```
c) The run time complexity of this is O(n) because it's using recursion. 

## Exercise II
```
Suppose that you have an n-story building and plenty of eggs. Suppose also that an egg gets broken if it is thrown off floor f or higher, and doesn't get broken if dropped off a floor less than floor f. Devise a strategy to determine the value of f such that the number of dropped + broken eggs is minimized.
```
For this problem I would probably use recursion to solve the problem and start off with the first floor and work my way up to determine which floor the egg starts to break. Because I'm using recursion, the space time complexity of my proposed solution would be O(n).
