---
layout: default
title: Publications
permalink: /publications/

description: the list of scientific publications of the lab

nav_bar: true
nav_order: 5

years: [2023, 2022, 2021, 2020, 2019, 2018, 2017]
---


Our up-to-date publication list is also available on [Google Scholar](https://scholar.google.com/citations?user=LuA1j4oAAAAJ&oi=ao).

<div class="container" style="text-align: justify">
Jump to: 
{% for y in page.years %}
<a href="#{{y}}" style="padding-right:10px; padding-left:10px">{{y}}</a>
{% endfor %}
<a href="#older_pubs" style="padding-right:10px; padding-left:10px">Pre-2017</a>
</div>



<div class="bib_section" style="padding-top: 20px">
  <h4 class="year" id="older_pubs">Preprints</h4>
    {% bibliography -f all -q @*[note=preprint] %}
  
  {% for y in page.years %}
    <h4 class="year" id="{{y}}">{{y}}</h4>
    {% bibliography -f all -q @*[year={{y}} && note!=preprint] %}
  {% endfor %}

  <h4 class="year" id="older_pubs">Older publications (pre 2017)</h4>
  {% bibliography -f all -q @*[year<=2016] %}

</div>



