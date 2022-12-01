---
layout: page
title: JinHyun Han
title_s1: Ph.D. Student
title_s2: University of Seoul
description: hanj617 [at] hanmail.net
img: assets/img/jhan.jpeg
importance: 8
category: current
---

### Short Bio

<p>JinHyun Han is a Ph.D. student in the <a href="https://engineering.uos.ac.kr/engineering/index.do?epTicket=LOG">Department of Computer Science and Engineering</a> at the <a href="https://www.uos.ac.kr/">University of Seoul</a>. He received his M.S. in <a href="http://infocom.ssu.ac.kr/kor/main/">Underwater Acoustic Communication</a> and B.S. in <a href="http://infocom.ssu.ac.kr/kor/main/">Information and Communication Engineering</a> at the <a href="https://ssu.ac.kr/">Soongsil University</a>. He is currently a Deputy General Manager at <a href="https://www.ust21.co.kr/">UST21</a>.</p>

### Education
<ul>
<li>Ph.D. Computer Science, University of Seoul 2021 - Present.
</li>
<li>M.S. Underwater Acoustic Communication, Soongsil University, 2010.
</li>
<li>B.S. Information and Communication Engineering, Soongsil University, 2008.
</li>
</ul>

### Employment History
<ul>
<li>Research Intern, Human-Centered Artificial Intelligence Lab (HCAIL), University of Seoul, Seoul, Korea from March 2021.
</li>
<li>Deputy General Manager, UST21, Incheon, Korea from 2017 to 2022.
</li>
</ul>

### Professional Activities
<ul>
<li>Commissioner; University-Industry Collaboration AI Convergence Research Center, Inha University.
</li>
</ul>

### Honors & Awards
<ul>
<li>Minister's Commendation from Ministry of Oceans and Fisheries,  The Government of the Republic of Korea, 2020.
</li>
</ul>

For more information, visit Han's [LinkedIn](https://www.linkedin.com/in/jin-hyun-han-2556029b/).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>