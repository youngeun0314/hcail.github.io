---
layout: page
title: Yunjung Bae
title_s1: Undergraduate Research Intern
title_s2: University of Southern California
description: lbae [at] usc.edu
img: assets/img/yjbae.png
importance: 16
category: current
---

### Short Bio
<p>Yunjung Bae is an undergraduate student majoring in <a href="https://dornsife.usc.edu/cognitive-science">Cognitive Science</a> at the <a href="https://www.usc.edu/">University of Southern California</a>. She is a research intern at the <a href="http://hcail.github.io">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>. She is a recipient of the 2022 <a href="https://dornsife.usc.edu/scholarship-descriptions/#haltom">Margaret P. and Paul T. Haltom, Sr. Endowed Scholarship</a>.</p>

### Education
<ul>
<li>B.A. Cognitive Science, University of Southern California 2020-Present.
</li>
</ul>

### Employment History
<ul>
<li>Research Intern, Human-Centered Artificial Intelligence Lab (HCAIL), University of Seoul, Seoul, Korea from May 2022.
</li>
</ul>

### Professional Activities
<ul>
<li>Student Volunteer, ACM ASSETS 2022.
</li>
<li>Student Volunteer, ACM RecSys 2022.
</li>
<li>Student Volunteer, SIGCHI Korea Local Chapter Summer Event 2022.
</li>
<li>Student Volunteer, ACM FAccT 2022.
</li>
</ul>

### Honors & Awards
<ul>
<li>Margaret P. and Paul T. Haltom, Sr. Endowed Scholarship, University of Southern California, 2022.
</li>
<li>Academic Achievement Award (AAA), University of Southern California 2021-2022.
</li>
</ul>

For more information, visit Bae's [personal website](https://yunjung-bae.github.io/).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>