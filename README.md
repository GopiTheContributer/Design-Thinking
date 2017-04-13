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

















Srcs:
http://www.programmingforbiologists.org/material/problem-decomposition/
http://www.bbc.co.uk/education/guides/zqqfyrd/revision/1
https://www.wethinq.com/en/blog/2016/03/15/Design-thinking-for-big-problems.html
https://medium.com/the-many/the-problem-with-design-thinking-988b88f1d696
