---
layout: page
title: Minki Chun
title_s1: M.S. Student
title_s2: University of Seoul
description: cna81136 [at] uos.ac.kr
img: assets/img/mchun.png
importance: 4
category: current
---

### Short Bio
<p>Minki Chun is a masters student in <a href="https://engineering.uos.ac.kr/engineering/depart/cs/welcome.do">Computer Science</a> at <a href="https://www.uos.ac.kr/">University of Seoul</a>, Korea. He received his B.S. degree in <a href="https://ice.dongguk.edu/main">Information Communication Engineering</a> from <a href="https://www.dongguk.edu/">Dongguk University</a>, Korea, in 2020. His research interests include deep learning, explainable AI, and user experience. He is a recipient of the <a href="https://www.autoeverapp.kr">Hyundai AutoEver (Barrier Free App Development Contest)</a> Excellent Prize and <a href="https://sigchi.org/awards/gary-marsden-travel-awards/">ACM SIGCHI Gary Marsden Travel Awards</a>.</p>

### Education
<ul>
<li>Masters student in Computer Science, University of Seoul from 2020.
</li>
<li>B.S. Information Communication Engineering, Dongguk University, 2020.
</li>
</ul>

### Employment History
<ul>
<li>Research Intern, Human-Centered Artificial Intelligence Lab (HCAIL), University of Seoul, Seoul, Korea from Feb. 2020.
</li>
<li>Teaching Assistant (Discrete Mathematics, Programming Language), University of Seoul, Seoul, Korea from Mar. 2020 to June 2021.
</li>
<li>Teaching Assistant (Visual Programming), Dongguk University, Seoul, Korea from Sep. 2019 to Dec. 2019.
</li>
<li>Intern in Human Resource Department, Korea Invention Promotion Association, Seoul, Korea from Jan. 2018 to Feb. 2018.
</li>
</ul>

### Professional Activities
<ul>
<li>Student Volunteer Chair, SIGCHI Korea Local Chapter Summer Event 2022.
</li>
<li>Student Volunteer, ACM FAccT 2022.
</li>
<li>Student Volunteer, ACM IUI 2021.
</li>
</ul>

### Honors & Awards
<ul>
<li>Excellence Prize, Hyundai AutoEver Barrier Free App Development Contest, 2022.
</li>
<li>University of Seoul Travel Grant, 2021.
</li>
<li>Gary Marsden Travel Awards, ACM SIGCHI, 2021.
</li>
</ul>

For more information, visit Chun's [personal website](https://sites.google.com/view/minkichun/).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>