---
layout: page
title: Wanhae Lee
title_s1: Research Intern
title_s2: KakaoCorp
description: iwanhae [at] gmail.com
img: assets/img/wlee.png
importance: 19
category: current
---



###Short Bio
<p>Wanhae Lee is a software engineer at <a href="https://www.kakaocorp.com/page/?lang=en">KakaoCorp</a>, CloudPlatform Team and a research intern at the <a href="http://hcail.github.io">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>. He received his B.S. in <a href="ttps://engineering.uos.ac.kr/engineering/depart/cs/welcome.do">Computer Science and Engineering</a> from the <a href="https://www.uos.ac.kr/">University of Seoul</a> in 2022.</p>

### Education
<ul>
<li>B.S. Computer Science, University of Seoul, 2022
</li>
</ul>

### Employment History
<ul>
<li>Research Intern, Human-Centered Artificial Intelligence Lab (HCAIL), University of Seoul, Seoul, Korea from Nov. 2022.
</li>
<li>Software Engineer, KakaoCorp, Seoul, Korea from July 2020.
</li>
</ul>

### Professional Activities
<ul>
<li>XXX
</li>
</ul>

### Honors & Awards
<ul>
<li>XXX
</li>
</ul>

For more information, visit Lee's [personal website](https://iwanhae.github.io/wanhae-lee).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
