---
layout: default
permalink: /people/
title: People
description: the machines in motion lab team

nav_bar: true
nav_order: 1
---

<div class="row align-items-top justify-content-around">
{% for person in site.data.members %}
<div class="col-sm-12 col-md-6" style="padding-bottom: 30px">
  <div class="row justify-content-center">
    <div class="col">
    {% if person.website %}
    <a href="{{person.website}}">
    {% endif %}
      <img style="border-radius:50%; float: right; max-height: 120px; max-width: 120px;" src="{{ person.image | prepend: '/assets/img/' | prepend: site.baseurl }}" alt="photo of {{person.name}}">
    {% if person.website %}
    </a>
    {% endif %}
    </div>
    <div class="col people">
      <div class="name">{{person.name}}</div>
      <div class="position">{{person.position}}</div>
    </div>
  </div>
</div>
{% endfor %}
</div>

---

<h2> Past members</h2>
{% for person in site.data.alumni %}
<!-- The paddingtop and margin-top edits allow anchors to link properly. -->
<div class="row" style="padding-left: 20px">
<span>
  <b>{{person.name}}</b>{% if person.description %}, {{person.description}} {% endif %}
</span>
</div>
{% endfor %}

