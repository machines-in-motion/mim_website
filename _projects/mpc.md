---
layout: project
title: Model-predictive control


project_order: 1
image: projects/mpc.jpg
bibliography: mpc

videos:
  - https://www.youtube.com/embed/Oz5eYBGoiok
  - https://www.youtube.com/watch?v=xzCn1nQiVPI
---

Computing a globally optimal control policy is generally intractable, especially when hard constraints need to be satisfied.
Model-predictive control (MPC) circumvents the issue by instead re-computing at every control cycle an optimal control "trajectory",
 i.e. a sequence of optimal actions to be taken from the current state of the system.
Hence, the controller needs to solve an optimization problem at each control cycle to find a command that optimizes 
the future behavior of the robot.
This approach enables the creation of very versatile and reactive behaviors. A simple change in the cost function
defining the goal of the controller leads to a different behavior without the need for a new algorithm.
We are also guaranteed that optimal actions are taken at every instant of time while ensuring constraint satisfaction.

However, the use of MPC on real, complex robots, lead to important challenges, as the dynamics of complex robots is typically nonlinear and
often non-smooth, which leads to non-convex optimization problems which need to be solved at a very high frequency.
In this research focus, we tackle these issues to create generic algorithms for MPC that can be used on any types of robots.
In particular:
1. We develop generic MPC algorithms that can be used with any types of robots
2. We design efficient solvers that exploit the structure of robotics problems and modern optimization techniques
3. We use machine learning to speed-up optimization
4. We demonstrate our algorithms on complex tasks with legged robots and manipulators