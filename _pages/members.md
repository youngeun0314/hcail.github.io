---
layout: page
title: people
permalink: /members/
description: as of April 2022
nav: true
display_categories: [current, alumni]
horizontal: false
---

<!-- pages/members.md -->
<div class="projects">
{%- if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_projects = site.members | where: "category", category -%}
  {%- assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
  {% endfor %}

{%- else -%}
<!-- Display projects without categories -->
  {%- assign sorted_projects = site.members | sort: "importance" -%}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
{%- endif -%}
</div>

<table style="width:100%">
<tr>
  <td class="c2">Woohyun Cho</td>
  <td class="c2">Undergraduate Research Intern</td>
  <td class="c2">University of Michigan</td>
  <td class="c2">Summer 2021</td>
</tr>
  <tr>
    <td class="c2">Joonyoung Jun</td>
    <td class="c2">Undergraduate Research Intern</td>
    <td class="c2">University of Washington</td>
    <td class="c2">Spring 2020 - Fall 2021</td>
  </tr>
  <tr>
    <td class="c2">Jeongjin Park</td>
    <td class="c2">Undergraduate Research Intern</td>
    <td class="c2">Purdue University</td>
    <td class="c2">Spring 2021 - Spring 2021</td>
  </tr>
  <tr>
    <td class="c2">Hyuk Gi Lee</td>
    <td class="c2">Research Intern</td>
    <td class="c2">University of Washington</td>
    <td class="c2">Summer 2020 - Spring 2021</td>
  </tr>
  <tr>
    <td class="c2">Jihyeon Park</td>
    <td class="c2">Undergraduate Research Intern</td>
    <td class="c2">Cornell University</td>
    <td class="c2">Summer 2020 - Spring 2021</td>
  </tr>
  <tr>
    <td class="c2">Haeul Lee</td>
    <td class="c2">Undergraduate Research Intern</td>
    <td class="c2">University of Seoul</td>
    <td class="c2">Fall 2020 - Winter 2020</td>
  </tr>
  <tr>
    <td class="c2">Changgeon Lim</td>
    <td class="c2">Undergraduate Research Intern</td>
    <td class="c2">University of Seoul</td>
    <td class="c2">Fall 2020 - Winter 2020</td>
  </tr>
  <tr>
    <td class="c2">Wanhae Lee</td>
    <td class="c2">Undergraduate Research Intern</td>
    <td class="c2">Kakao Corp.</td>
    <td class="c2">Fall 2019 - Winter 2020</td>
  </tr>
  <tr>
    <td class="c2">Suin Gwak</td>
    <td class="c2">Undergraduate Research Intern</td>
    <td class="c2">University of Seoul</td>
    <td class="c2">Fall 2019 - Winter 2020</td>
  </tr>
  <tr>
    <td class="c2">Jaewon Choi</td>
    <td class="c2">Undergraduate Research Intern</td>
    <td class="c2">University of Washington</td>
    <td class="c2">Summer 2020 - Fall 2020</td>
  </tr>
  <tr>
    <td class="c2">Minji Kwon</td>
    <td class="c2">Undergraduate Research Intern</td>
    <td class="c2">Kyung Hee University</td>
    <td class="c2">Fall 2019 - Spring 2020</td>
  </tr>
  <tr>
    <td class="c2">Yewon Hyun</td>
    <td class="c2">Undergraduate Research Intern</td>
    <td class="c2">POSTECH</td>
    <td class="c2">Fall 2019 - Winter 2019</td>
  </tr>
  <tr>
    <td class="c2">Heejae Jung</td>
    <td class="c2">Undergraduate Research Intern</td>
    <td class="c2">Kyung Hee University</td>
    <td class="c2">Fall 2018 - Summer 2019</td>
  </tr>
  <tr>
    <td class="c2">Minyeong Seo</td>
    <td class="c2">Undergraduate Research Intern</td>
    <td class="c2">Kyung Hee University</td>
    <td class="c2">Spring 2019 - Summer 2019</td>
  </tr>
  <tr>
    <td class="c2">Yiji Bae</td>
    <td class="c2">Undergraduate Research Intern</td>
    <td class="c2">Kyung Hee University</td>
    <td class="c2">Fall 2018 - Spring 2019</td>
  </tr>
  <tr>
    <td class="c2">Hyeonjin Jeon</td>
    <td class="c2">Undergraduate Research Intern</td>
    <td class="c2">Kyung Hee University</td>
    <td class="c2">Fall 2018 - Winter 2018</td>
  </tr>
</table>
