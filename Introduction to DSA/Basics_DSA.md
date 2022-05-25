1. Data structures are used to represent data efficiently. Data representation methods are arrays, linked list and
   trees. Algorithms are used to develop a step-by-step procedure for performing a task.
    
2. When we implement an algorithm, we have to choose a data structure to perform the task.

3. There can be many solutions/algorithms to solve a particular problem, but we choose the most efficient one.

4. The efficiency of an algorithm depends on the running time and the memory it occupies. To determine efficiency of
   an algorithm, check how the algorithm behaves when the input size is increased.
    
5. The running time of an algorithm increases with the increase in input size. (Asymptotic Analysis)
<hr>

 <b>Big O Notation</b>: How fast a function f(n) grows as n becomes large.

f(n) is O(g(n)) , if there exists c and n0 such that<br>
f(n) <= c*g(n) , for all n >= n0

Order of g(n):<br>Slow Growth --> Fast Growth<br> 
               1 --> log(n) --> n --> nlog(n) --> n^2 --> n^3 --> n^k --> 2^n --> 3^n --> k^n --> n!

For finding Big O, 
- Keep the fastest growing term and discard the lower terms and constants
- Ignore coefficients
- If f(n) is constant, then we say that f(n) is O(1)
- Base of logarithm is not important
- For g(n) function, always choose the tight/least upper bound and ignore all the other loose upper bounds

For Big O Analysis of Algorithms, 
- Express the running time as function of input size(n)
- T(n) = running time in terms of n
- Find Big O for function T(n)

Example:<br>
Algorithm A --> T(n) = 6n^3 + log(n) + 2n        --> O(n^3)<br>
Algorithm B --> T(n) = 5n + n^2 + 12             --> O(n^2)<br>
Algorithm C --> T(n) = 7n + 10log(n) + 2         --> O(log(n))<br>
Algorithm D --> T(n) = n^2 + 15                  --> O(n^2)

Out of the 4 given algorithms, Algorithm C is the best because it's rate of growth is the least.
