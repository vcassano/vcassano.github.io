<!-- ---
layout: page
title: publications
permalink: /publications/
order: 2
# ignore: true
description: >
  <p> List of latest publications by categories in reversed chronological order.
  A more complete list can be found in my <a href="https://dblp.org/pers/c/Cassano:Valentin.html">DBLP</a> section. </p>
years: [2023, 2022, 2021, 2020, 2019, 2018]
nav: true
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div> -->

---
layout: page
title: publications
permalink: /publications/
order: 2
description: >
  <p> List of latest publications. Full list also available on 
  <a href="https://dblp.org/pid/140/7429.html">DBLP</a>. </p>
nav: true
---

<iframe src="https://dblp.org/pid/140/7429.html" 
        width="100%" 
        height="800px" 
        frameborder="0">
</iframe>