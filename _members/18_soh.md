---
layout: page
title: Seungyoung Oh
title_s1: Undedrgraduate Research Intern
title_s2: University of Seoul
description: dhtmddud08 [at] gmail.com
img: assets/img/soh.png
importance: 18
category: current
---

### Short Bio
<p>Seungyoung Oh is an undergraduate research intern at the <a href="http://hcail.github.io">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>. He expects to receive his B.S. in <a href="https://engineering.uos.ac.kr/engineering/depart/cs/welcome.do">Computer Science</a> from the <a href="https://www.uos.ac.kr/">University of Seoul</a> in Feb. 2024.</p>

### Education
<ul>
<li>Pursuing a B.S. in Computer Science, University of Seoul.
</li>
</ul>

### Employment History
<ul>
<li>Undergraduate Research Intern, HCAIL, University of Seoul, Seoul, Korea from June 2022.
</li>
</ul>

### Professional Activities
<ul>
<li>Student Volunteer, SIGCHI Korea Local Chapter Summer Event 2022.
</li>
</ul>

For more information, visit Oh's [personal website](https://jackine08.github.io/jackine08/).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
