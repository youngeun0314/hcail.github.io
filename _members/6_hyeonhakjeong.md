---
layout: page
title: Hyeonhak Jeong
title_s1: M.S. Student
title_s2: University of Seoul
description: drummycrane [at] gmail.com
img: assets/img/hjeong.jpeg
importance: 6
category: current
---

### Short Bio
<p>Hyeonhak Jeong is a masters student in <a href="https://engineering.uos.ac.kr/engineering/depart/cs/welcome.do">Computer Science</a> at <a href="https://www.uos.ac.kr/">University of Seoul</a>.</p>

### Education
<ul>
<li>Masters student in Computer Science, University of Seoul from 2021.
</li>
<li>B.S. Computer Science and Engineering, University of Seoul, 2021.
</li>
</ul>

### Employment History
<ul>
<li>Research Assistant, Human-Centered Artificial Intelligence Lab (HCAIL), University of Seoul, Seoul, Korea from Feb. 2021.
</li>
<li>Undergraduate Research Intern, Human-Centered Artificial Intelligence Lab (HCAIL), University of Seoul, Seoul, Korea from July 2020 to Feb. 2021.
</li>
</ul>

### Professional Activities
<ul>
<li>Student Volunteer, ACM ASSET 2021-2022.
</li>
<li>Student Volunteer Chair, SIGCHI Korea Local Chapter Summer Event 2022.
</li>
<li>Student Volunteer, ACM FAccT 2022.
</li>
<li>Student Volunteer, ACM TEI 2022.
</li>
<li>Student Volunteer, MobileHCI 2021.
</li>
<li>Student Volunteer, ACM CHI 2021.
</li>
<li>Student Volunteer, ACM IUI 2021.
</li>
<li>Student Volunteer, ACM CSCW 2020.
</li>
</ul>

### Honors & Awards
<ul>
<li>Travel Grant, University of Seoul, 2021.
</li>
</ul>

For more information, visit Jeong's [personal website](https://drummycrane.github.io/info/).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>