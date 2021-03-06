#Flatten List

*There is a list which contains integers or other nested lists which may contain yet more lists and integers which then… you get the idea. You should put all of the integer values into one flat list. The order should be as it was in the original list with string representation from left to right.*

###Input
A nested array with arrays or integers.

###Output
The one-dimensional array with integers.

###Example
```javascript
flatList([1, 2, 3]) // [1, 2, 3]
flatList([1, [2, 2, 2], 4]) // [1, 2, 2, 2, 4]
flatList([[[2]], [4, [5, 6, [6], 6, 6, 6], 7]]) // [2, 4, 5, 6, 6, 6, 6, 6, 7]
flatList([-1, [1, [-2], 1], -1]) // [-1, 1, -2, 1, -1]
```

###Precondition
	depth < 10

###How it is used
This concept is useful for parsing and analyzing files with complex structures and the task challenges your creativity in writing short code.
