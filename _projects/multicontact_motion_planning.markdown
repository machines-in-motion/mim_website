---
layout: page
title: Multi-Contact Rapid Motion Planning
description: 
img: 
importance: 1
category: decision-making and control
---

When robots walk, run, jump or move in general, they need to interact with their environment (walls, ground etc...) and create the necessary forces. Consequently, it is crucial for the robot to decide when and where it should interact or make contact with its environment and what forces it needs to exert on its environment to achieve its desired motion. At the same time it is also important for the robot to make such decisions quickly so that they can react to external disturbances, changes in environment etc.  Despite its importance, this area still remains an open problem mainly because of the difficulty in handling discontinuity in dynamics during contact and non linearity in robot dynamics during motion planning along with other issues. We use both optimization and machine learning techniques to develop generic frameworks that enable robots to make the required contact & motion planning decisions quickly with minimal input.  



---
## related publications
<div class="publications">

{% bibliography --file multicontact_motion_planning %}

</div>