## Office Hour Notes
The following notes were compiled from office hours (Spring 2024).

### NP Theory
This is the essence of theoretical computing. Can a problem be solved efficiently?  We measure runtime based on the input size.

For a given input of size `n`: 
* **Polynomial Time:** `O(n^k)` for some constant `k`. These are _efficient_ problems to solve.
* **Exponential Time:** `O(k^n)` for some `k > 1`. These are _hard_ problems to solve.

Terminology:
* **P**: Polynomial Time
* **NP**: Non-deterministic Polynomial Time

### Non-Deterministic Polynomial Time
What does non-deterministic polynomial time mean? 
It means a problem could be solved in polynomial time **if** the computer is non-deterministic.

#### What do we mean by that? 
Think of an all-knowing oracle. Whenever it has to make a choice, it makes the right choice.

Think of the Traveling Salesman Problem (TSP). Whenever you get to a city, you choose the right next city to go to. This is non-deterministic. 

_You're always making the best choice, regardless of the number of choices._

In other words, non-deterministic polynomial time means that you can solve the problem in polynomial time on a non-deterministic computer. (You may thank Alan Turing for this, who came up with these ideas.) 

However, the rub is that all of the computers that we work with today are deterministic. 

If we take the TSP problem, if you get to a city and you got to pick the next city, you have to re-evaluate them all and go through all of the permutations. This is what a deterministic computer does. 

If we had a non-deterministic computer, we could solve TSP quickly. However, we cannot today. 

There is hope that quantum computing will give us the non-deterministic computer because it can examine all computers at once. 

### The Class of Problems
We think of problems as belonging to a class. 
* **Class P**: A solution may be found in polynomial time (easy)
* **Class NP**: A solution may be verified in polynomial time
* **NP Hard**: We are yet to find a polynomial-time solution
* **NP Complete**: Both in NP and at least as hard as NP Hard problems

A problem is either **known** or **yet to be known** to be in P or NP.



