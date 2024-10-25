java c
MAST20018 – Discrete Mathematics and Operations Research
Assignment 4
Upload to  Gradescope by 5pm  Wed 16th  October 2024
Question 1
Consider the following linear programming model:
max z = x1 + 2x2 + 3x3
subject to
x1 + 2x2 + 3x3 ≤ 10
x1 + x2            ≤ 5
x1                    ≤ 1
x1, x2, x3 ≥ 0
a) Find an optimal solution to the problem using the simplex algorithm with Bland’s rule. After you obtain the final tableau, write down the value of all variables and objective function.
b) Looking at the final tableau, how do you conclude that the solution is not unique?
c) Doing pivot operations, find an alternative optimal solution and write down the value of all variables and objective function. If there are many possible entering variables that would lead to an alternative optimal solution, choose the one with the smallest index.
Question 2
Consider the linear program
Maximize 4x1 + 3x2 − x3
subject to
x1 + 2x2 − x3 ≥ 4
x1 + x2 ≤ 8
2x1 − x2 ≤ 10
x1, x2, x3 ≥ 0
and solve it using the two-phase simplex algorithm with Bland’s rule.
Question 3
The Big-M method is an adaptation of the Simplex Algorithm which is used as an alternative to the Two-Phase Simplex 代 写MAST20018 – Discrete Mathematics and Operations Research Assignment 4
代做程序编程语言method. A pseudo-code for the Big-M method is as follows:
ALGORITHM Big-M
Require: An LP in canonical form. with objective max z = f(x) and artificial variables y1 , ...,yp
Ensure: An optimal solution to the LP or a statement that the LP is infeasible or unbounded
1:  Let M be a very large constant
2:  Modify the objective of the LP to max z′ = f(x) − Mεi(p)=1 yi
3:  Employ  the  standard Simplex Algorithm to solve the LP with the modified objective.   The Optimality Criterion is satisfied when there are no more negative reduced costs in the columns
of the non-artificial variables
Consider the following Linear Program:
max z = x1 + x2
s.t.
x1 + x2 ≥ 1
2x1 + 3x2 ≤ 12
3x1 + 2x2 ≤ 12
x1, x2 ≥ 0
a)  Express the problem in canonical form. and solve using the Big-M simplex method with Bland’s rule.  When solving the problem, you should not substitute  M by a big number, but rather explicitly use the symbol M in your computations.
b)  Sketch the feasible region and identify the extreme point associated to each tableau you obtained in (a).
Hint: remember that you can only proceed with tableau operations once your tableau is in canonical form.

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
