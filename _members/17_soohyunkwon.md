---
layout: page
title: Soohyun Kwon
title_s1: Undergraduate Research Intern
title_s2: New York University
description: sk7905 [at] nyu.edu
img: assets/img/shkwon.png
importance: 17
category: current
---

### Short Bio
<p>Soohyun Kwon is an undergraduate research intern at <a href="http://hcail.github.io">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>. She is expecting to receive her Bachelor’s degrees in <a href="https://as.nyu.edu/departments/psychology">Psychology</a> and <a href="https://cds.nyu.edu">Data Science</a> from <a href="https://www.nyu.edu">New York University (NYU)</a> by Dec 2023.</p>

### Education
<ul>
<li>B.A. Psychology and Data Science, New York University 2019-Present.
</li>
</ul>

### Employment History
<ul>
<li>Undergraduate Research Intern, HCAIL, University of Seoul, Seoul, Korea from May 2022.
</li>
</ul>

### Professional Activities
<ul>
<li>Student Volunteer, ACM CSCW 2022.
</li>
<li>Student Volunteer, ACM RecSys 2022.
</li>
<li>Student Volunteer, SIGCHI Korea Local Chapter Summer Event 2022.
</li>
<li>Student Volunteer, ACM FAccT 2022.
</li>
</ul>

For more information, visit Kwon's [personal website](https://skwon017.github.io).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
