## 03/20 Office Hour Notes 
Notes taken from 03/21 office hours. 
You need to understand the concepts and how these things work. We are looking to test your fundamental understanding of the material. Go through the practice problems in HW7, the recommended practice problems. Working through these things manually will reinforce the concepts.

Hints:
- You should understand the strategy behind simplex. 
- We are not asking you to solve simplex in the context of the exam
- Understand it to the extent the lectures go over it

### Format of a Linear Program
Every linear program begins with a **objective function** which is either a **maximization** or a **minimization**.

Here we are maximizing `2x + 3y`. In addition, our objective function is subject to a series of constraints. 
* The first is the non-negativity constraint. This gives us our first set of potential values. Any point in the below shaded region is a potential value for `x` and `y`

![lp1.png](imgs/lp1.png)

* Once we have our non-negativity constraints, we get a series constraints across our different variables

![lp2.png](imgs/lp2.png)
![lp3.png](imgs/lp3.png)
![lp4.png](imgs/lp4.png)

```
Objective Function: max 2x + 3y
Constraints: x, y >= 0
             x - y <= 5
             x + 2y <= 8
             -x + 3y <= 9
```
We're constraining the possible values for `x` and `y` such that they meet these constraints. The points in the shaded area satisfy all of these constraints and is the **feasible region**.

A linear program that is **infeasible** does not have any solution.

![lp5.png](imgs/lp5.png)

The optimal value will be a point on the boundary region of the polyhedron which is formed by the intersection of all of the constraints.

### Finding Optimal Value of a Linear Program


### Feasible vs. Infeasible 


### Bounded vs. Unbounded


### Converting between Primal and Dual


### Duality Theorem