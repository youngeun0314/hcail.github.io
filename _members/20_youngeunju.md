---
layout: page
title: Youngeun Ju
title_s1: Undergraduate Research Intern
title_s2: University of Seoul
description: blueseanvgm [at] uos.ac.kr
img: assets/img/yju.png
importance: 20
category: current
---

### Short Bio
<p>Youngeun Ju is an undergraduate research intern at <a href="http://hcail.github.io">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>. She is expecting to receive her B.S. in <a href="https://engineering.uos.ac.kr/engineering/depart/cs/welcome.do">Computer Science</a> from <a href="https://www.uos.ac.kr/">University of Seoul</a> by Feb.2026.</p>

### Education
<ul>
<li>Pursuing a B.S. in Computer Science, University of Seoul 2022-Present.
</li>
</ul>

### Employment History
<ul>
<li>Undergraduate Research Intern, HCAIL, University of Seoul, Seoul, Korea from Jan.2023.
</li>
</ul>

### Professional Activities
<ul>
<li>Not yet.
</li>
</ul>

For more information, visit Ju's [personal website](https://youngeun0314.github.io/).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
