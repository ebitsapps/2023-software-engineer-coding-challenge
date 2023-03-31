# 2023 Software Engineering Candidates Coding Challenge

Thank you for your interest in the Software Engineer position at EBITS. We appreciate the time you've taken to apply and would like you to participate in a coding challenge as the next step in our evaluation process.

The coding challenge consists of five questions that will help us assess your problem-solving skills, data structures, and algorithm knowledge. You can use any programming language of your choice to solve these problems.

Please find below detailed instructions, input format, output format, and additional requirements for each question.

**Question 1 - Array Manipulation**

Given an array of integers, write a function that takes the array and an
integer \'k\' as input parameters, and rotates the array to the right by
\'k\' positions. Your function should not use any additional data
structures and should work in O(n) time complexity, where \'n\' is the
length of the array.

*Input Format:*

-   An array of integers, **arr** (1 \<= arr.length \<= 10\^5, -10\^4 \<= arr\[i\] \<= 10\^4)

-   An integer **k** (0 \<= k \<= arr.length)

*Output Format:*

-   The array of integers after rotating it to the right by **k** positions.

**Question 2 - REST API Pagination**

Imagine you are building a REST API for a blogging platform. 
Your API should return a paginated list of blog posts. Explain
how you would design the API endpoint to handle pagination (page number
and page size) and write a function that takes an array of blog post
objects, page number, and page size as input parameters and returns the
paginated results.

*Input Format:*

-   An array of blog post objects, **posts** (1 \<= posts.length \<= 10\^4)

-   An integer **pageNumber** (1 \<= pageNumber \<= totalPages)

-   An integer **pageSize** (1 \<= pageSize \<= 100)

*Output Format:*

-   An array of blog post objects, representing the paginated result.

**Question 3 - Cache Implementation**

Describe a caching mechanism you would implement to reduce the number of
database queries for frequently accessed data in an application. 
Implement a simple function that simulates fetching data
from the cache or the database based on the cache\'s status (hit/miss).

*Input Format:*

-   A string **cacheStatus** representing the status of the cache (\"hit\" or \"miss\")

-   A string **data** representing the data to be fetched (1 \<= data.length \<= 100)

*Output Format:*

-   A string representing the fetched data.

**Question 4 - String Compression**

Write a function that takes a string as input and compresses it using
the following rules:

-   Replace consecutive repeating characters with the character followed by
the number of repetitions.

-   If the compressed string is not shorter than the original, return the
original string. For example, given the input string \"aaabbcddd\", the
function should return \"a3b2c1d3\".

*Input Format:*

-   A string **inputString** consisting of lowercase English letters (1 \<= inputString.length \<= 10\^4)

*Output Format:*

-   A string representing the compressed string, or the original string if the compressed version is not shorter.

**Question 5 - Tree Traversal**

Consider a hierarchical structure representing categories in an
e-commerce platform, where each category has a name and a list of
subcategories. Implement a function that takes the root category as
input and returns an array containing the names of all categories in the
hierarchy using a depth-first search (DFS) traversal.

*Input Format:*

-   A **CategoryNode** object representing the root category. Each **CategoryNode** object has the following properties:

    -   **name**: a string representing the category name (1 \<= name.length \<= 100)

    -   **subcategories**: an array of **CategoryNode** objects representing the subcategories

*Output Format:*

-   An array of strings containing the names of all categories in the hierarchy, traversed using depth-first search (DFS).
