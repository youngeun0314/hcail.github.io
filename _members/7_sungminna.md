---
layout: page
title: Sungmin Na
title_s1: Research Intern
title_s2: University of Washington
description: sungminna97 [at] gmail.com
img: assets/img/sna.png
importance: 7
category: current
---

### Short Bio
<p>Sungmin Na is a social media coordinator at <a href="https://www.engageadx.com/">EngageADX</a> and a research intern at the <a href="http://hcail.github.io">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>. She received her B.A. in <a href="https://soc.washington.edu//">Sociology </a>at the <a href="https://www.washington.edu/">University of Washington </a>in 2020.</p>

### Education
<ul>
<li>B.A. Sociology, University of Washington, 2020.
</li>
</ul>

### Employment History
<ul>
<li>Research Intern, HCAIL, University of Seoul, Seoul, Korea from Oct. 2020.
</li>
<li>Social Media Coordinator, EngageADX, Inc. from Sept. 2019.
</li>
</ul>

### Professional Activities
<ul>
<li>Reviewer, ACM CSCW 2022 Poster.
</li>
<li>Student Volunteer, W4A 2022.
</li>
<li>Student Volunteer, ACM UIST 2021-2022.
</li>
<li>Student Volunteer, ACM ASSETS 2021-2022.
</li>
<li>Student Volunteer, ACM RecSys 2021-2022.
</li>
<li>Student Volunteer, SIGCHI Korea Local Chapter Summer Event 2022.
</li>
<li>Student Volunteer, ACM FAccT 2022.
</li>
<li>Student Volunteer, ACM DIS 2021.
</li>
</ul>

### Honors & Awards
<ul>
<li>Gary Marsden Travel Awards, ACM SIGCHI.
</li>
</ul>

For more information, visit Na's [personal website](https://sungminna97.wixsite.com/my-site).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
