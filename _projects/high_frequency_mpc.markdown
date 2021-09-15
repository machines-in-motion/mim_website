---
layout: page
title: High frequency MPC - 1KHz and Beyond
description: 
img: 
importance: 1
category: decision-making and control
---

For robotic systems to act robustly in a dynamic environment, it is vital to be able to   react quickly to uncertainties and changes in the surroundings. Model Predictive Control (MPC) is a promising framework as it  enables to automatically plan and adapt optimal trajectories online using sensor information. . However, since in MPC a finite horizon optimal control problem needs to be solved every few milliseconds, and the corresponding optimization problem is normally non-convex, solving this problem in real-time is a challenge. In our group, we study novel approaches to make the MPC feedback loop as efficient as possible.


---
## related publications
<div class="publications">

{% bibliography --file high_frequency_mpc %}

</div>