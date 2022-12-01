---
layout: page
title: Taewon Yoo
title_s1: Undergraduate Research Intern
title_s2: Kyung Hee University
description: twyoo [at] khu.ac.kr
img: assets/img/tyoo.png
importance: 5
category: current
---

### Short Bio
<p>Taewon Yoo is a software engineer at <a href="https://www.pentasecurity.co.kr">Penta Security Systems Inc.</a> and an undergraduate research intern at the <a href="http://hcail.github.io">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>. He is also pursuing a B.S. in <a href="http://swcon.khu.ac.kr/">Software Convergence</a>, concentration in Data Science, at <a href="https://www.khu.ac.kr">Kyung Hee University</a>. </p>

### Education
<ul>
<li>Undergraduate student in Software Convergence (Data Science Track), Kyung Hee University, from 2017.
</li>
</ul>

### Employment History
<ul>
<li>Software Engineer, Penta Security Systems Inc., Seoul, Korea from Aug. 2021 (alternative military service).
</li>
<li>Research Intern, Human-Centered Artificial Intelligence Lab (HCAIL), University of Seoul, Seoul, Korea from Feb. 2020.
</li>
<li>Research Intern, KIST Europe Forschungsgesellschaft mbH, Saarbrücken, Germany from Aug. 2019 to Jan. 2020.
</li>
</ul>

### Professional Activities
<ul>
<li>Student Volunteer, ACM CSCW, Oct. 2021.
</li>
<li>Student Volunteer, ACM ASSESTS, Oct. 2021.
</li>
<li>Student Volunteer, ACM RecSys, Sep. 2021.
</li>
<li>Student Volunteer, ACM DIS, June 2021.
</li>
<li>Student Volunteer, ACM IUI, April 2021.
</li>
<li>Student Volunteer, IEEE Student Volunteer Program, Aug. 2020 - Jan. 2021.
</li>
</ul>

### Honors & Awards
<ul>
<li>Excellence Prize, Hyundai AutoEver Barrier Free App Development Contest, 2022.
</li>
<li>National Scholarship for Science and Engineering, Korea Aid Foundation, 2019.
</li>
<li>National Scholarship for Excellence in Software, 2019.
</li>
</ul>

For more information, visit Yoo's [personal website](https://tw-yoo.github.io/).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>