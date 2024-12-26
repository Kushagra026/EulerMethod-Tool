# EulerMethod-Tool
 created a Python tool that solves Ordinary Differential Equations (ODEs) using Euler's method, a simple numerical technique. This method approximates the solution to an ODE of the form:

𝑑
𝑦
𝑑
𝑡
=
𝑓
(
𝑡
,
𝑦
)
dt
dy
​
 =f(t,y)
where 
𝑓
(
𝑡
,
𝑦
)
f(t,y) is a function that defines the relationship between 
𝑡
t and 
𝑦
y. Given an initial condition 
𝑦
(
𝑡
0
)
=
𝑦
0
y(t 
0
​
 )=y 
0
​
 , Euler's method iteratively calculates the solution at discrete time steps using the formula:

𝑦
𝑛
+
1
=
𝑦
𝑛
+
ℎ
⋅
𝑓
(
𝑡
𝑛
,
𝑦
𝑛
)
y 
n+1
​
 =y 
n
​
 +h⋅f(t 
n
​
 ,y 
n
​
 )
Where:

ℎ
h is the step size (time increment),
𝑡
𝑛
t 
n
​
  is the current time,
𝑦
𝑛
y 
n
​
  is the current approximation of the solution at time 
𝑡
𝑛
t 
n
​
 .
The tool takes the following inputs:

The function 
𝑓
(
𝑡
,
𝑦
)
f(t,y) representing the ODE,
The initial condition 
𝑦
0
y 
0
​
 ,
The start and end times for the solution,
The step size 
ℎ
h.
It computes the solution at each time step and returns both the time values and corresponding solution approximations. The results are then plotted using Matplotlib to visualize how the solution evolves over time.

This tool is useful for solving simple ODEs where an analytical solution may be difficult to obtain or when a quick numerical solution is needed.
