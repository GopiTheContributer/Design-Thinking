# Design-Thinking


Design Thinking: Learn How to Solve Problems Like a Designer

4 essential elements of computational thinking:
   1.Decomposition
   2.Abstract thinking
   3.Pattern-recogonition
   4.Algorithims

What is decomposition?
     Decomposition is one of the four cornerstones of Computer Science. It involves breaking down a complex problem or system into smaller parts that are more manageable and easier to understand. The smaller parts can then be examined and solved, or designed individually, as they are simpler to work with.

What is abstraction?
      It involves filtering out – essentially, ignoring - the characteristics that we don't need in order to concentrate on those that we do.

https://github.com/reach2arunprakash/Design-Thinking/blob/master/large.png

       We noted that all cats have general characteristics, which are common to all cats, eg eyes, a tail, fur, a liking for fish and the ability to make meowing sounds. In addition, each cat has specific characteristics, such as black fur, a long tail, green eyes, a love of salmon, and a loud meow. These details are known as specifics.

In order to draw a basic cat, we do need to know that it has a tail, fur and eyes. These characteristics are relevant. We don't need to know what sound a cat makes or that it likes fish. These characteristics are irrelevant and can be filtered out. We do need to know that a cat has a tail, fur and eyes, but we don't need to know what size and colour these are. These specifics can be filtered out.


Recursive Decomposion : Algorithimic approach

Divide-and-Conquer is a widely deployed strategy for writing sequential algorithms. In it, a problem is divided into subproblems, which are again divided into subproblems recursively until a trivial solution can be calculated. Afterwards, the results of the subproblems are merged together when needed. This strategy can be applied as is to achieve a recursive problem decomposition. As the smaller tasks are usually independent of one another, they can be calculated in parallel, often leading to well-scaling parallel algorithms. Parallel sorting algorithms often use recursive decompositions.

Data Decomposition : Functional thinking style

When data structures with large amounts of similar data need to be processed, data decomposition is usually a well-performing decomposition technique. The tasks in this strategy consist of groups of data. These can be either input data, output data or even intermediate data, decompositions to all varieties are possible and may be useful. All processors perform the same operations on these data, which are often independent from one another. This is my favorite decomposition technique, because it is usually easy to do, often has no dependencies in between tasks and scales really well.

Functional Decomposition: Object oriented thinking

For functional decomposition, the functions to be performed on data are split into multiple tasks. These tasks can then be performed concurrently by different processes on different data. This often leads to so-called Pipelines. Although this decomposition technique is usually easy to do as well, it often does not scale too well, because there is only a limited amount of functions available in each program to split up.

Where to start :

Decomposition in practice

We do many tasks on a daily basis without even thinking about – or decomposing – them, such as brushing our teeth.
Example 1: Brushing our teeth

To decompose the problem of how to brush our teeth, we would need to consider:

    which toothbrush to use
    how long to brush for
    how hard to press on our teeth
    what toothpaste to use

Example 2: Solving a crime

It is only normally when we are asked to do a new or more complex task that we start to think about it in detail – to decompose the task.

Imagine that a crime has been committed. Solving a crime can be a very complex problem as there are many things to consider.

For example, a police officer would need to know the answer to a series of smaller problems:

    what crime was committed
    when the crime was committed
    where the crime was committed
    what evidence there is
    if there were any witnesses
    if there have recently been any similar crimes

The complex problem of the committed crime has now been broken down into simpler problems that can be examined individually, in detail.




    Abstraction & Design
        Have you ever seen OO go bad?  What happened?  What elements of OO design are most prone to abuse and misuse? What are some ways to prevent these mishaps?
        Implement a game of tic-tac-toe.  How do you represent the game board?  What interfaces do you expose?
        Implement a stock ticker.  How do you handle displaying all of the data quickly to the end user? // Since most people are familiar with stocks I generally have them articulate the requirements and functionality first.  The crux of this problem is thinking about the different granularities in which they can view a stock price – real time, hourly, daily, yearly, etc. and modeling their data to support fast querying for those graphs.
        You are tasked with designing software that runs and controls elevators.  What interfaces and class objects would you use?  What configuration options would you need for the software to work in skyscrapers, buildings with only one elevator, and buildings with banks of elevators?  How would these use cases change the objects and interfaces in your design?
        Imagine you were tasked with designing a text editor (or instant messaging program).  What are the primary functions?  What are the various interfaces, classes, etc. that you would need to provide those functions? // and feel free to replace text editor with any common small program of your choosing (mobile apps make great examples)

    Algorithms (different approaches and performance)
        Describe the algorithm for a depth-first graph traversal.  // It is also useful to have the candidate tell you about the data structure they are using to represent the graph.
        Write a function that takes two strings as arguments and returns a string containing only the characters found in both strings. Have them write 2 versions – one that is O(n) and one that is O(n^2).
        You are given a sorted array and you want to find the number N. How do you do the search as quickly as possible (not just traversing each element)?
            How would the performance of your algorithm change if there were lots of duplicates in the array?
        Given a list of numbers that is a circular list, such that iterating through the list would return the first number after you reached the end. How might you find the minimum number in the list?  // It is easier if you can assume all the numbers are increasing, until it reaches the end of the list.Implement a function that will divide two numbers without using the division operator. (solution for dividing a number by 3)
            Now find any given number in the list. What is the upper bound on for the running time of this function?
        Given two different lists of objects, come up with an efficient solution to find the intersection of the two lists. (solution)
        How do you find all the permutations of a string? What is the running time?
            Now imagine that the string has repeating characters. How could you modify your solution so it would only find unique permutations as efficiently as possible?
        Given a list of numbers, assume each number represents the amount of time it takes to execute a task.  How would you dive the tasks across two different servers to they finished in the same amount of time?Write a program that will find the 10 most popular words (popularity is determined by how often they occur) in a file. How can you do this efficiently in terms of space?  In terms of time? // Sometimes it helps to tell them it is a really big file that can’t fit in memory if they get hung up on timing
            How would you divide them across N servers?
            Now assume you want the jobs to finish at the same time, what is the optimal number of servers and how would you distribute the jobs across them to achieve this goal?
        Given an array what is the longest contiguous increasing subsequence of elements?  (solution) What is the longest increasing subsequence? (solution) (This is a classic dynamic programming problem)
        Imagine that you want to return a random number from a really long linked list of numbers. You do not know the length of it, but it is big. Write a function which will return a random number from the list. (solution)
        Create an algorithm that will output the results of rolling a die (1-6) using a function that simulates a coin toss (1 or 2). All 6 outcomes should be equally likely. (solution)
        Given an array of integers write a program that will determine if any two numbers add up to a specified number N. Do this without using hash tables. (solution, although some use hash tables)















Srcs:
http://www.programmingforbiologists.org/material/problem-decomposition/
http://www.bbc.co.uk/education/guides/zqqfyrd/revision/1
https://www.wethinq.com/en/blog/2016/03/15/Design-thinking-for-big-problems.html
https://medium.com/the-many/the-problem-with-design-thinking-988b88f1d696
