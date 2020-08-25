# TheFarmProblem
It's a classical problem in linear optimization.

Linear programming (LP, also called linear optimization) is a method to achieve the best outcome (such as maximum profit or lowest cost) in a mathematical model whose requirements are represented by linear relationships. Linear programming is a special case of mathematical programming (also known as mathematical optimization).

John owns a small 45-hectare farm and wants to plant corn and beans. Each hectare of corn generates a profit of US $ 200 and each hectare of beans returns US $ 300 in profit. 
The number of employees and fertilizers needed for each hectare are described in the table below, Considering that John has 100 employees and 120 tons of fertilizers, how can he maximize his profit?



|              |   Corn   |    Beans    |
|Employees     |     3    |      2      |
|Fertilizers   |  2 Ton   |   4 Ton     |


=============== Resolution =================

Decision variables:

x1 = hectares with corn
x2 = hectares with beans

Max profit (L): 200*x1 + 300*x2

Restrictions:

(Area): x1 + x2 = 45
(Employees): 3*x1 + 4*x2 <= 100
(Fertilizers): 2*x1 + 4*x2 <= 120

x1, x2 >= 0
