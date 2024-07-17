---
layout: default
permalink: /research/
title: Research
description: research activities of the laboratory

nav_bar: true
nav_order: 2
---

<h2 id="research">Current activities</h2>
<div class="row align-items-top justify-content-around">
    {% for project in site.projects  %}
    <div class="col-sm-12 col-md-4 col-lg-4 text-center" style="padding-bottom: 30px">
        <a href="{{ project.url | prepend: site.baseurl}}">
        <div class="row align-items-top">
        <div class="col-sm-12">
            <img src="{{ project.image | prepend: '/assets/img/' | prepend: site.baseurl }}" alt="image of {{project.title}}" class="img-fluid" style="width:220px; height=auto">
        </div>
            <div class="col-sm-12" style="font-size: 1.2rem;">{{ project.title }}</div>
        </div>
        </a>
    </div>
    {% endfor %}
</div>

---

<h2 id="software">Software</h2>
<p>Most of our software is open-source and available on the laboratory <a href="https://github.com/machines-in-motion">Github</a>. In particular, you might be interested in the following packages:    
    <ul>
        <li><a href="https://github.com/machines-in-motion/mim_solvers">MimSolver</a>, an efficient sparse SQP solver for nonlinear trajectory optimization and MPC with hard constraints.</li>
        <li><a href="https://github.com/machines-in-motion/biconvex_mpc">BiConMP</a>, a solver for whole-body nonlinear trajectory optimizer used on a variety of legged robots, both for closed-loop MPC and offline trajectory generation.</li>
        <li><a href="https://github.com/machines-in-motion/dynamic_game_optimizer">A stagewise Newton method</a> for dynamic game control with imperfect state observation</li>
        <li><a href="https://github.com/machines-in-motion/irisc">iRiSC</a>, an efficient solver for risk sensitive optimal control for nonlinear systems with imperfect observations</li>
        <li><a href="https://github.com/machines-in-motion/contact_mcts">Contact planning</a> for object manipulation using Monte-Carlo Tree Search and learned value functions using trajectory optimization</li>
    </ul> 
All our contributions related to ODRI are available on the
      <a href="https://github.com/open-dynamic-robot-initiative">
        Open Dynamic Robot Initiative
      </a> Github. It includes hardware designs, low-level real-time control code, simulation tools and basic controllers for legged robots.
</p>
---

<h2 id="robots">Robots</h2>
<p>We work with a wide range of robots. Our laboratory has a Sarcos humanoid robot, a Bolt biped, several Solo12 quadrupeds, several manipulation and mobile platforms including a Kuka iiwa14 and a tri-finger platform.
Our laboratory consists of a 1000sqft fully sensorized space including a motion capture system. We also conduct large scale, collaborative experiments in a 3000sqft shared robotics experimental facility. The hardware designs
of the ODRI robots are open and can be found <a href="https://github.com/open-dynamic-robot-initiative/open_robot_actuator_hardware">here</a>. Check out our <a href="{{ site.youtube_link }}">Youtube channel</a> to see our robots moving!
</p>
<div class="container text-center">
        <img src="{{ 'sarcos.jpg' | prepend: '/assets/img/robots/' | prepend: site.baseurl }}" alt="image of the Sarcos humanoid" class="img-fluid" style="width:140px; height=auto">
        <img src="{{ 'solo12.jpg' | prepend: '/assets/img/robots/' | prepend: site.baseurl }}" alt="image of Solo12" class="img-fluid" style="width:220px; height=auto">
        <img src="{{ 'bolt.jpg' | prepend: '/assets/img/robots/' | prepend: site.baseurl }}" alt="image of bolt" class="img-fluid" style="width:160px; height=auto">
        <img src="{{ 'iiwa.jpg' | prepend: '/assets/img/robots/' | prepend: site.baseurl }}" alt="image of Kuka iiwa" class="img-fluid" style="width:140px; height=auto">
        <img src="{{ 'trifinger.jpg' | prepend: '/assets/img/robots/' | prepend: site.baseurl }}" alt="image of trifinger platform" class="img-fluid" style="width:180px; height=auto">
</div>

---

<h2 id="sponsors">Sponsors</h2>
We are grateful to our sponsors for their generous support.
Our current research is mainly supported by National Science Foundation grants
[1932187](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1932187)
[2026479](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2026479)
[2222815](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2222815) and
[2315396](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2315396)
and a generous donation from [Wandercraft](https://www.wandercraft.eu/). 

We are also grateful to our previous sponsors and donors, including the European Union’s Horizon 2020 research and innovation programme, the European Research Council,
OPPO, Intel, Meta, NYU Wireless, Google and NSF grants [1925079](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1925079) and [1825993](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1825993)