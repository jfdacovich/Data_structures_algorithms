# Data_structures_algorithms
- **Big O**

Big-O notation is the language we use for talking about how long an algorithm takes to run (time complexity) or how much memory is used by an algorithm (space complexity). Big-O notation can express the best, worst, and average-case running time of an algorithm. For our purposes here, we are going to focus primarily on Big-O as it relates to time complexity.

**CheatSheet**
- **O(1)** Constant – no loops
- **O(log N)** Logarithmic – usually searching algorithms have log n if they are sorted (Binary Search)
- **O(n)** Linear – for loops, while loops through n items
- **O(n log(n))** Log Linear – usually sorting operations
- **O(n^2)** Quadratic – every element in a collection needs to be compared to ever other element. Two
nested loops
- **O(2^n)** Exponential – recursive algorithms that solves a problem of size N
- **O(n!)** Factorial – you are adding a loop for every element
- **Iterating through half a collection is still O(n)**
- **Two separate collections: O(a * b)**
