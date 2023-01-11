---
layout: page
title: Jihyun Lee
title_s1: Research Intern
title_s2: Kyung Hee University
description: 2018102130 [at] khu.ac.kr
img: assets/img/jlee.png
importance: 5
category: alumni
---

### Short Bio
<p>Jihyun Lee is a research intern at <a href="http://hcail.github.io">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>. She received her B.S. in <a href="http://swcon.khu.ac.kr/">Software Convergence</a> in 2022 at <a href="https://www.khu.ac.kr">Kyung Hee University</a>.</p>

### Education
<ul>
<li>B.S. Software Convergence, Kyung Hee University, 2022.
</li>
</ul>

### Employment History
<ul>
<li>Undergraduate Research Intern, HCAIL, University of Seoul, Seoul, Korea from 2019.
</li>
</ul>

### Professional Activities
<ul>
<li>Student Volunteer, ACM ASSETS 2021.
</li>
<li>Student Volunteer, ACM DIS 2021.
</li>
</ul>

### Honors & Awards
<ul>
<li>Best Presentation Award, Asian CHI Symposium 2020.
</li>
<li>Excellence Award, KHU Software Festival 2019.
</li>
</ul>

For more information, visit Lee's [personal website](https://sites.google.com/khu.ac.kr/2azy/).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
