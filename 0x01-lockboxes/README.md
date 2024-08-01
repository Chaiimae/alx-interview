Pascal's Triangle

Pascal's Triangle is a triangular array of numbers in which each entry is the sum of the two numbers directly above it. The topmost row of the triangle starts with a single number 1. Subsequent rows are formed by adding pairs of numbers from the row above, with the edges of the triangle filled with 1s.

The triangle is named after the French mathematician Blaise Pascal, though it was studied by mathematicians in India, Persia, China, and Italy long before his time. It has many applications in mathematics, including combinatorics, algebra, and probability.

Key Properties:

Symmetry: The triangle is symmetric.
Binomial Coefficients: The 
𝑛
nth row corresponds to the coefficients of the expansion of 
(
𝑎
+
𝑏
)
𝑛
(a+b) 
n
 .
Each row starts and ends with 1: This is because there is only one way to choose all or none from a set


example: 
       1
      1 1
     1 2 1
    1 3 3 1
   1 4 6 4 1
Each number is the sum of the two directly above it. For example, in the third row, 2 is obtained by adding the two 1s above it.

Pascal's Triangle is a simple yet powerful tool for understanding patterns and solving various mathematical problems.

Must Know
For this project, you will need a solid understanding of several key concepts in order to develop a solution that can efficiently determine if all boxes can be opened. Here’s a list of concepts and resources that will be instrumental in tackling this project:

Concepts Needed:
Lists and List Manipulation:

Understanding how to work with lists, including accessing elements, iterating over lists, and modifying lists dynamically.
Python Lists (Python Official Documentation)
Graph Theory Basics:

Although not explicitly required, knowledge of graph theory (especially concepts related to traversal algorithms like Depth-First Search or Breadth-First Search) can be very helpful in solving this problem, as the boxes and keys can be thought of as nodes and edges in a graph.
Graph Theory (Khan Academy)
Algorithmic Complexity:

Understanding the time and space complexity of your solution is important, as it can help in writing more efficient algorithms.
Big O Notation (GeeksforGeeks)
Recursion:

Some solutions might require a recursive approach to traverse through the boxes and keys.
Recursion in Python (Real Python)
Queue and Stack:

Knowing how to use queues and stacks is crucial if implementing a breadth-first search (BFS) or depth-first search (DFS) algorithm to traverse through the keys and boxes.
Python Queue and Stack (GeeksforGeeks)
Set Operations:

Understanding how to use sets for keeping track of visited boxes and available keys can optimize the search process.
Python Sets (Python Official Documentation)
By reviewing these concepts and utilizing these resources, you will be well-equipped to develop an efficient solution for this project, applying both your algorithmic thinking and Python programming skills.
