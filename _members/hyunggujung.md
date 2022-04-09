---
layout: page
title: Hyunggu Jung
title_s1: HCAIL Director
title_s2: University of Seoul
description: hjung [at] uos.ac.kr
img: assets/img/profhjung.png
importance: 1
category: current
---

### Short Bio
<p>Hyunggu Jung is an assistant professor of <a href="https://www.uos.ac.kr/engineering/depart/cs/welcome.do">Computer Science and Engineering</a> and an assistant professor
of <a href="https://www.uos.ac.kr/engineering/depart/ai/welcome.do">Artificial Intelligence</a> at the <a href="https://www.uos.ac.kr/en/main.do">University of Seoul</a>
    and directs <a href="http://hcail.github.io">HCAIL</a>.
    He was an assistant professor of <a href="http://swcon.khu.ac.kr/">Software Convergence</a> at <a href="http://www.khu.ac.kr/eng">Kyung Hee University</a> from April 2018 to August 2019.
    He received his Ph.D. in <a href="http://www.bhi.washington.edu">Biomedical and Health Informatics</a> in 2017, under the supervision of Drs. <a href="http://faculty.washington.edu/pth">Peter Tarczy-Hornoch</a> and <a href="https://www.hcde.washington.edu/zachry">Mark Zachry</a>, at the <a href="http://www.uwmedicine.org">University of Washington School of Medicine</a>. He received his B.S. in <a href="https://cs.kaist.ac.kr">Computer Science</a> and a minor in Business Economics from <a href="http://www.kaist.edu/html/en/index.html">Korea Advanced Institute of Science and Technology (KAIST)</a> in 2008, and his M.Math. degree from the <a href="https://uwaterloo.ca">University of Waterloo</a> in 2010, under the supervision of <a href="https://cs.uwaterloo.ca/~rcohen/">Prof. Robin Cohen</a>, and his M.S. degree with a <a href="http://hci.stanford.edu">Human-Computer Interaction (HCI)</a> specialization from <a href="http://www.stanford.edu">Stanford University</a> in 2012.
    He is a recipient of the <a href="http://www.niied.go.kr/user/nd76648.do">Korean Government Scholarship</a> and <a href="http://mogamfoundation.or.kr">Mogam Science Scholarship</a>.</p>

### Education
<ul>
<li>Ph.D. Biomedical and Health Informatics, University of Washington School of Medicine, 2017
</li>
<li>M.S. Computer Science, Stanford University, 2012
</li>
<li>M.Math. Computer Science, University of Waterloo, 2010
</li>
<li>B.S. Computer Science with a minor in Business Economics, KAIST, 2008
</li>
</ul>

### Employment History
<ul>
<li>Department Chair, Department of Computer Science and Engineering, University of Seoul, Seoul, Korea from Mar. 2021.
</li><li>
Assistant Professor, Department of Artificial Intelligence, University of Seoul, Seoul, Korea from Aug. 2020.
</li><li>
Assistant Professor, Department of Computer Science and Engineering, University of Seoul, Seoul, Korea from Sep. 2019.
</li><li>
Assistant Professor, Department of Software Convergence, Kyung Hee University, Yongin, Korea from Apr. 2018 to Aug. 2019.
</li><li>
Predoctoral Research Associate, Division of Biomedical and Health Informatics, University of Washington, Seattle, WA from Sep. 2014 to Dec. 2017.
</li><li>
Research Intern, Computer Science Lab, PARC, a Xerox Company, Palo Alto, CA from Jun. 2015 to Sep. 2015.
</li><li>
Research Intern, Natural Interaction Research Group, Microsoft Research, Redmond, WA from Jun. 2013 to Sep. 2013.
</li><li>
Research Assistant, Stanford Center for Biomedical Informatics Research, Stanford University, Stanford, CA from Sep. 2010 to Aug. 2011.
</li><li>rch Assistant, Artificial Intelligence Research Group, University of Waterloo, Waterloo, ON, Canada from Sep. 2008 to Aug. 2010.
</li>
</ul>

### Professional Activities
<ul>
<li>
Associate Chair, ACM CSCW 2021-Present
</li>

<li>
Officer, Korea ACM SIGCHI Chapter 2018-Present
</li>

<li>Associate Chair, ACM CHI 2021 Late-Breaking works track
</li>

<li>Assistant Editor, MedInfo Editorial Team 2017
</li>

<li>
Co-organizer, Workshop on Social Media for Older Adults 2016
</li>

<li>
Web Chair, ACM ICMI 2015
</li>

<li>
Student Volunteer, ACM CHI 2015-2018
</li>

</ul>

### Honors & Awards
<ul>
<li>
Korean-American Scientists and Engineers Association (KSEA) & Korea-U.S. Science Cooperation Center (KUSCO) Scholarship, 2015.
</li><li>
The Korean Computer Scientists and Engineers Association Scholarship, 2014.
</li><li>
Korean Government Scholarship, 2012-2014.
</li><li>
Mogam Science Scholarship, 2012.
</li><li>
Best Project Award, CS247@Stanford, 2012.
</li><li>
KAIST Humanity Scholarship, 2008.
</li></ul>

For more information, visit Dr. Jung's [personal website](http://hyunggujung.com/).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
