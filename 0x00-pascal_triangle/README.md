Pascal's Triangle

Pascal's Triangle is a triangular array of numbers in which each entry is the sum of the two numbers directly above it. The topmost row of the triangle starts with a single number 1. Subsequent rows are formed by adding pairs of numbers from the row above, with the edges of the triangle filled with 1s.

The triangle is named after the French mathematician Blaise Pascal, though it was studied by mathematicians in India, Persia, China, and Italy long before his time. It has many applications in mathematics, including combinatorics, algebra, and probability.

Key Properties:

Symmetry: The triangle is symmetric.
Binomial Coefficients: The 
𝑛th row corresponds to the coefficients of the expansion of (a+b)n.
Each row starts and ends with 1: This is because there is only one way to choose all or none from a set.

Example: 
       1
      1 1
     1 2 1
    1 3 3 1
   1 4 6 4 1

Each number is the sum of the two directly above it. For example, in the third row, 2 is obtained by adding the two 1s above it.

Pascal's Triangle is a simple yet powerful tool for understanding patterns and solving various mathematical problems.

Must Know
To successfully complete this project, you should revise the following Python concepts:

Lists and List Comprehensions:

Understand how to create, access, modify, and iterate over lists.
Utilize list comprehensions for more concise and readable code, especially for generating rows of Pascal’s Triangle.
Functions:

Know how to define and call functions.
Pass parameters and return values, particularly how to return a list of lists representing Pascal’s Triangle.
Loops:

Use for and while loops to iterate through sequences.
Nested loops may be necessary for generating each row and calculating the values of Pascal’s Triangle.
Conditional Statements:

Apply if, elif, and else conditions to implement logic based on the position within Pascal’s Triangle (e.g., the edges of the triangle always being 1).
Recursion (Optional):

While not strictly necessary, understanding recursion can provide an alternative approach to generating Pascal’s Triangle.
Recognize base cases and recursive cases for a function that generates the triangle’s rows.
Arithmetic Operations:

Perform addition, a fundamental operation for calculating each element of Pascal’s Triangle as the sum of the two elements directly above it.
Indexing and Slicing:

Access elements and slices of lists, crucial for identifying and summing the correct elements when constructing each row of the triangle.
Memory Management:

Be mindful of how lists are stored and copied, especially when creating new rows based on the values of the previous row.
Error and Exception Handling (Optional):

Use try-except blocks as needed to handle potential errors, such as invalid input types or values.
Efficiency and Optimization:

Consider the time and space complexity of different approaches to generating Pascal’s Triangle.
Evaluate and apply optimizations to improve the performance of the solution.
By revisiting these concepts, you will be well-prepared to tackle the challenges of implementing Pascal’s Triangle in Python, applying both your mathematical understanding and programming skills to develop an efficient and effective solution.
