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

### Short Bio
<p>Wanhae Lee is a software engineer at <a href="https://www.kakaocorp.com/page/?lang=en">KakaoCorp</a>, CloudPlatform Team and a research intern at the <a href="http://hcail.github.io">Human-Centered Artificial Intelligence Lab (HCAIL)</a> under the supervision of <a href="http://hyunggujung.com">Prof. Hyunggu Jung</a>. He received his B.S. in <a href="ttps://engineering.uos.ac.kr/engineering/depart/cs/welcome.do">Computer Science and Engineering</a> from the <a href="https://www.uos.ac.kr/">University of Seoul</a> in 2022.</p>

### Education
<ul>
<li>B.S. Computer Science, University of Seoul, 2022
</li>
</ul>

### Employment History
<ul>
<li>Research Intern, HCAIL, University of Seoul, Seoul, Korea from Nov. 2022.
</li>
<li>Software Engineer, KakaoCorp, Seoul, Korea from July 2020.
</li>
<li>Teaching Assistant (Discrete Mathematics), University of Seoul, Seoul, Korea, from Mar. 2020 to June 2020.
</li>
</ul>

### Professional Activities
<ul>
<li>Speaker, if(kakao)dev, KakaoCorp 2022.
</li>
<li>Speaker, OpenInfra & Cloud Native Days Korea 2022.
</li>
<li>Speaker, KubeCon + CloudNativeCon North Armerica, CNCF 2022.
</li>
</ul>

### Honors & Awards
<ul>
<li>Academic Excellence Award, University of Seoul, Spring 2020.
</li>
<li>Academic Excellence Award, University of Seoul, Spring & Fall 2017.
</li>
<li>Top award, SemTeulJe (Software Competition), Department of Computer Science and Engineering, University of Seoul , 2016.
</li>
<li>Seoul Mayor's Award for Excellent Achievement, Seoul Metropolitan City, 2016.
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
