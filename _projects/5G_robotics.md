---
layout: project
title: 5G robotics


project_order: 4
image: projects/5Grobotics.jpg
bibliography: 5Grobotics

---

Wireless communication based on fifth generation (5G) technology offers unprecedented opportunities for the deployment of mobile robots in industry and consumer environments as it promises both high data bandwidth and low latency communication. This in turn enables mobile robots to remotely execute computationally demanding perception, planning and control algorithms instead of executing them locally. In particular, the low-latency guarantees of 5G wireless can potentially be leveraged to offload even fast millisecond-scale force and torque control loops to the edge. At the same time, the rich multi-modal sensor data that mobile robots use for visual perception can be transmitted over high data-rate 5G links. Further, 5G enables high-throughput robot-to-robot communication, enabling complex interactions between teams of robots. Finally, the directionality of mmWave signals enable to further use wireless as a sensor modality for localization purposes. Together, these new capabilities can enable mobile robots with improved autonomy, range, form-factor, cost and reliability.

In this line of research, in collaboration wireless and low-power computing experts Profs. <a href="https://engineering.nyu.edu/faculty/elza-erkip">E. Erkip</a>, <a href="https://engineering.nyu.edu/faculty/siddharth-garg">S. Garg</a>, and <a href="https://engineering.nyu.edu/faculty/sundeep-rangan">S. Rangan</a> at NYU,
we investigate how 5G wireless can benefit robotics. In particular:
1. We investigate methods to offload the computation of optimization-based control loops to the network edge
2. We build <a href="https://github.com/huaijiangzhu/delay_robust_invdyn">robot simulations</a> and <a href="https://github.com/nyu-wireless/mmwRobotNav">datasets</a> that incorporate realistic 5G transmission modeling
3. We design algorithms to plan under wireless transmission uncertainty, e.g. to locate a wireless emitter or maximize reception coverage during robot movement

This project is mainly supported by the National Science Foundation National Robotics Initiative grant <a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=1925079&HistoricalAwards=false">NRI: FND: Action-perception loops over 5G millimeter wave wireless for cooperative manipulation</a>. Part of the work has also been partially supported by a grant from OPPO.