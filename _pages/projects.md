---
layout: default
permalink: /projects/
title: Research
description: 

nav_bar: true
nav_order: 2
---

<h3>Current activities</h3>
<div class="row align-items-top justify-content-around">
    {% for project in site.projects  %}
    <div class="col-sm-12 col-md-6 col-lg-4 text-center" style="padding-bottom: 30px">
        <a href="{{ project.url }}">
        <div class="row align-items-top">
        <div class="col-sm-12">
            <img src="{{ project.image | prepend: '/assets/img/' | prepend: site.baseurl }}" alt="image of {{project.title}}" class="img-fluid" style="width:75%; height=auto">
        </div>
            <div class="col-sm-12" style="font-size: 1.3rem;">{{ project.title }}</div>
        </div>
        </a>
    </div>
    {% endfor %}
</div>
    
<!-- <div class="col-sm-12 col-md-6 col-lg-4">
        Model predictive control
    </div>
    <div class="col-sm-12 col-md-6 col-lg-4">
        Stochastic and risk-sensitive optimal control
    </div>
    <div class="col-sm-12 col-md-6 col-lg-4">
        Learning to control
    </div>
    <div class="col-sm-12 col-md-6 col-lg-4">
        5G robotics
    </div>
    <div class="col-sm-12 col-md-6 col-lg-4">
        Legged locomotiom
    </div>
    <div class="col-sm-12 col-md-6 col-lg-4">
        Robotic manipulation
    </div>
    <div class="col-sm-12 col-md-6 col-lg-4">
        Open Dynamic Robot Initiative
    </div>
    <div class="col-sm-12 col-md-6 col-lg-4">
        Socially responsible science
    </div> -->

<h3>Past projects</h3>


<h3>Sponsors</h3>
We are grateful to our sponsors the generous support of our research.
Our current research is mainly supported by the National Science Foundation grants
[1925079](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1925079&HistoricalAwards=false)
[1932187](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1932187&HistoricalAwards=false)
[2026479](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2026479&HistoricalAwards=false)
and
[2222815](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2222815&HistoricalAwards=false),
Meta and New York University.

We are also grateful to our previous sponsors, including the European Union’s Horizon 2020 research and innovation programme, the European Research Council,
OPPO, NYU Wireless and Google.