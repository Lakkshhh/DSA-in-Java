Data structures are used to represent data efficiently. Data representation methods are arrays, linked list and
trees. Algorithms are used to develop a step-by-step procedure for performing a task.
    
When we implement an algorithm, we have to choose a data structure to perform the task.

There can be many solutions/algorithms to solve a particular problem, but we choose the most efficient one.

The efficiency of an algorithm depends on the running time and the memory it occupies. To determine efficiency of
  an algorithm, check how the algorithm behaves when the input size is increased.
    
The running time of an algorithm increases with the increase in input size. (Asymptotic Analysis)

 - Big O Notation: How fast a function f(n) grows as n becomes large.

f(n) is O(g(n)) , if there exists c and n0 such that
f(n) <= c*g(n) , for all n >= n0

Order of g(n): Slow Growth ---> Fast Growth ==== 1, log(n), n, nlog(n), n^2, n^3, n^k, 2^n, 3^n, k^n, n!

For finding Big O, 
- Keep the fastest growing term and discard the lower terms and constants
- Ignore coefficients
- If f(n) is constant, then we say that f(n) is O(1)
- Base of logarithm is not important
