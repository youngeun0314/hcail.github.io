---
layout: page
title: Hyunmin Lee
title_s1: Undergraduate Research Intern
title_s2: University of Seoul
description: yunoa64 [at] gmail.com
img: assets/img/hmlee.png
importance: 12
category: current
---

### Short Bio
<p>Hyunmin Lee is an undergraduate student majoring in <a href="https://engineering.uos.ac.kr/engineering/depart/cs/welcome.do">Computer Science</a> at the <a href="https://www.uos.ac.kr">University of Seoul</a>. He is a research intern at the <a href="http://hcail.github.io">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>.</p>

### Education
<ul>
<li>B.S. Computer Science, University of Seoul from 2019.
</li>
</ul>

### Employment History
<ul>
<li>Undergraduate Research Intern, Human-Centered Artificial Intelligence Lab (HCAIL), University of Seoul, Seoul, Korea from June 2021.
</li>
</ul>

### Professional Activities
<ul>
<li>Student Volunteer, CSCW 2022.
</li>
<li>Student Volunteer, SIGCHI Korea Local Chapter Summer Event 2022.
</li>
<li>Student Volunteer, ACM FAccT 2022.
</li>
</ul>

### Honors & Awards
<ul>
<li>Encouragement Award for University of Seoul Computer Algorithm Programming Contest division 2, University of Seoul, 2020.
</li>
<li>Scholorship for Academic Excellence, University of Seoul, Spring & Fall 2020.
</li>
</ul>

For more information, visit Lee's [personal website](https://yunoa64.github.io/).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>