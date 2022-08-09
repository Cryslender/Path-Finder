# Path-Finder
This is repository used for finding the path in pothole road 

## Document Description
The source code added to repository, is code that I use to find a path from a pothole rode. First the is a method that I use to get input from the user(which is the pothole road).Then check if the path exist usig boolean method(valid()) that will return true of false if no path exist. Again use booelean method(findEnd()) to check if goal node is there is the given input, if not return false or true if it there. After that I use BFS and DFS traversal to find the path and also to check which algorith is the fatest to find the path.

Problem solving statage I use:
1) Use of data structure to store the input data
2) Dynamic programming: I use it to recursively call the traversal method till it finds the goal or if not return string "goal not found", if found return string "goal found"