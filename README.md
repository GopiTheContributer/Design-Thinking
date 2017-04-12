# Design-Thinking


Design Thinking: Learn How to Solve Problems Like a Designer

Recursive Decomposion : Algorithimic approach

Divide-and-Conquer is a widely deployed strategy for writing sequential algorithms. In it, a problem is divided into subproblems, which are again divided into subproblems recursively until a trivial solution can be calculated. Afterwards, the results of the subproblems are merged together when needed. This strategy can be applied as is to achieve a recursive problem decomposition. As the smaller tasks are usually independent of one another, they can be calculated in parallel, often leading to well-scaling parallel algorithms. Parallel sorting algorithms often use recursive decompositions.

Data Decomposition : Functional thinking style

When data structures with large amounts of similar data need to be processed, data decomposition is usually a well-performing decomposition technique. The tasks in this strategy consist of groups of data. These can be either input data, output data or even intermediate data, decompositions to all varieties are possible and may be useful. All processors perform the same operations on these data, which are often independent from one another. This is my favorite decomposition technique, because it is usually easy to do, often has no dependencies in between tasks and scales really well.

Functional Decomposition: Object oriented thinking

For functional decomposition, the functions to be performed on data are split into multiple tasks. These tasks can then be performed concurrently by different processes on different data. This often leads to so-called Pipelines. Although this decomposition technique is usually easy to do as well, it often does not scale too well, because there is only a limited amount of functions available in each program to split up.



















Srcs:
https://www.wethinq.com/en/blog/2016/03/15/Design-thinking-for-big-problems.html
https://medium.com/the-many/the-problem-with-design-thinking-988b88f1d696
