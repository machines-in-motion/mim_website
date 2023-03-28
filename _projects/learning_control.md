---
layout: project
title: Learning to control


project_order: 3
image: projects/mpc.png
bibliography: uncertainty

videos:
  - https://www.youtube.com/embed/Oz5eYBGoiok
  - https://www.youtube.com/watch?v=xzCn1nQiVPI
---

Model-predictive control is a control approach which consists in solving an optimal control
problem at every control cycle given the current state of the robot and its environment.
This means that at each control cycle, the controller finds a control command that tries
to optimize the future behavior of the robot.
This approach promises to create very versatile and reactive behaviors.

In this research focus:
1. We design numerically efficient optimizers tailored for robotics problems
2. We test our algorithms on complex tasks with legged robots and manipulators