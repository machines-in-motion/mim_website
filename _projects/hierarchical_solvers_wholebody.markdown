---
layout: page
title: Hierarchical Solvers for Whole-Body Control
description: 
img: /assets/img/research/heirarchical.png
importance: 1
category: decision-making and control
---

Controlling complicated kinematic structures like robots requires certain abstractions in order to make the control problem tractable. While this foremost addresses linearization of nonlinear robot descriptions and tasks, we can identify another simplification which is commonly found in robotics: weighting robotic tasks against each other in the resulting control (or optimization thereof) problem to solve. While there are strong arguments for it like the use of well established solvers and providing a certain level of intuitivity, there are also disadvantages to it: the weighting requires a deep understanding of the tasks and the desired resulting behaviour which only an experienced robotics engineer might have. Also it might not be a very good representation of the physical reality of the robot, for example when critical tasks like maintaining stability are weighted against other, non-critical tasks. It therefore has been proposed to introduce the notion of hierarchies into robot control. This enables making certain tasks strictly more important than others, let's say maintaining stability over a reaching task. This topic offers a large variety of possible research directions: from inverse kinematics and inverse dynamics control to analysis of the numerical optimization algorithms. 


---
## related publications
<div class="publications">

{% bibliography --file hierarchical_solvers_wholebody %}

</div>